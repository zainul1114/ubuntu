###### ######
# NOUVELLIE
###### ######

# SETTINGS UBUNTU (18.04 LTS) [USER = UBUNTU]



# MYSQL SERVER

## Create database ##
* Create:
CREATE DATABASE IF NOT EXISTS namedb;
* Select:
USE namedb;
* Dumped:
SOURCE dump.sql;

## Create user and grant all privileges ##
* Create user:
CREATE USER 'ubuntu'@'%' IDENTIFIED BY 'cdn-devs';
* Grant all privileges:
GRANT ALL PRIVILEGES ON *.* TO 'ubuntu'@'%' WITH GRANT OPTION;