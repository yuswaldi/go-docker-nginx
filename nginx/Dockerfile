# might consider nginx:mainline for latest
FROM nginx:stable  
ENV TERM xterm
RUN apt-get update \
	&& apt-get install -y htop procps curl net-tools\
	&& rm -rf /var/lib/apt/lists/*
RUN mkdir /code
RUN mkdir /content
WORKDIR /code
