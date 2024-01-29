# Unix based setup automation

## infrastructure as code

in this repo we are setting up everything needed for a local dev environment in different Operating Systems including Linux/Mac (No WINDOWS!!) using a combination of Kind , Localstack , Virtualbox to run labs easily!

### setup

- first you need to clone this repo

````shell
git clone https://github.com/miladhzzzz/unix-dev-automation.git
````

- then use different scripts located at /scripts directory to setup your environment

````shell
# for example you can use mac.sh from scripts directory
cd /scripts
chmod +x ./setup-mac.sh 
./mac.sh 
# for setting up linux you should do the same steps replace setup-mac.sh with setup-linux.sh
# we also use kali linux so 
````

- **we also have some custom setup scripts for example you can run setup-kali.sh for a custom Graphical kali dev environment**

````shell
# this will install all the things required to setup a kali to my taste (you can install other setup files if you dont want this!)
chmod +x ./setup-kali.sh
./setup-kali.sh
````