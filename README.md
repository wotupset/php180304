# php180304
TUTORIALDIR=src/php180304/php_gae_quickstart-2018-03-04-07-41


git clone https://github.com/GoogleCloudPlatform/appengine-php-guestbook.git $TUTORIALDIR

cd $TUTORIALDIR


git checkout phase0-helloworld

cat helloworld.php

cat app.yaml

dev_appserver.py --php_executable_path=/usr/bin/php-cgi $PWD

gcloud app deploy app.yaml --project php180304



