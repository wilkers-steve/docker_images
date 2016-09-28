FROM ubuntu:14.04
MAINTAINER Steve Wilkerson <wilkers.steve@gmail.com>

RUN apt-get update && apt-get install -y \
	openjdk-7-jdk \
	screen \
        wget
RUN wget https://s3.amazonaws.com/Minecraft.Download/versions/1.10.2/minecraft_server.1.10.2.jar
RUN chmod +x minecraft_server.1.10.2.jar

EXPOSE 25565 25575

VOLUME ["/data"]



