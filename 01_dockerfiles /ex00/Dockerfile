FROM alpine

MAINTAINER zkamran <zia.tokhi@gmail.com>

RUN apk update && \
    apk upgrade && \
    apk add vim

ENTRYPOINT vim

# How to build it?
# docker build -t ex00 .

# How to run it?
# docker run --rm -ti ex00