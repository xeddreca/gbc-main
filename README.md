Givebackcode main website

#clone repo

git clone http://github.com/xeddreca/gbc-main

#build docker image

docker build -t gbc-main:tag .

#run an instance of the image

docker run -it -p 80:80 gbc-main:tag

--
