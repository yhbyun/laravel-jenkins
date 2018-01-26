FROM node:7.2

RUN apt-get install -y git

# install yarn
RUN curl -o- -L https://yarnpkg.com/install.sh | bash
ENV PATH /root/.yarn/bin:$PATH
