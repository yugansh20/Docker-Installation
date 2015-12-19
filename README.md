# Docker-Installation

This installation is for Ubuntu 14.04 LTS.
Make sure the kernel is updated.
Get root privilages.

1. Install docker - apt-get install -y docker.io
2. Check docker version - docker -v
3. wget -qO- https://get.docker.com/gpg | apt-key add -
4. New container - docker run -it ubuntu /bin/bash
