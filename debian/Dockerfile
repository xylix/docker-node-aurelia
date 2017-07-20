FROM debian:stretch 

# aurelia needs git, current node solution needs curl and gpg
RUN apt-get update && apt-get -y install curl gpg git 
RUN curl -sL https://deb.nodesource.com/setup_6.x | bash -
RUN apt-get update && apt-get -y install nodejs
RUN npm install -g aurelia-cli
