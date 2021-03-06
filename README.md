# e-dental-re

E-Dental rewritten (See [last project repository](https://github.com/srph/e-dental)) in its own \`framework\`. 

## Installation

**Requirements**:

- PHP `>=v5.4`
- MySQL `>=v5.x`
- [Composer](https://getcomposer.org)

**(1)** Clone the repository

```bash
$ git clone https://github.com/srph/e-dental-re.git
```

**(2)** Setup the database.

```bash
$ cd e-dental-yolo # go to the clone directory
$ mysql -u <user> <pass> # access to mysql 
$ create database dental; # create the database
$ mysql -u <user> <pass> < db.sql # dump/import the sql query
```

**(3)** Install the dependencies

```bash
# make sure that you are currently in the project's root directory
$ composer install
```

**(4)** Okay!

If your machine does not have installed web server, you can use **PHP**'s built-in web-server, [`SAPI`](http://php.net/manual/en/features.commandline.webserver.php).

```
$ php -S localhost:8000
```

Otherwise, just setup your web-server, and then you're good to go!

## Changes

- This project does not have user avatars / file uploads.
- This has the `calendar` to improve the `Schedules` module UX. 
- Schedules from past dates are no longer manageable.

## Limitation

- Unlike the first version, we're putting up shitty pages instead of flash errors / messages.
- In terms of code, this is project was not written nor will be written to be secure.
- Bad practices all over the place.

## Acknowledgement

**e-dental-yolo** © 2015+, Kier Borromeo ([srph](https://github.com/srph)) and Jealian Menor ([lianjea](https://github.com/lianjea)). **e-dental-yolo** is released under the [MIT](mit-license.org) license.
