FROM debian:bookworm

RUN apt update \
  && apt install -y apache2

CMD [ "apachectl", "-D", "FOREGROUND" ]
