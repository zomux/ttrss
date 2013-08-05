Running on OpenShift
----------------------------

Create an account at http://openshift.redhat.com/

Create a PHP 5 application + a PostgreSQL 8 cartridge to the app, and import all the quickstart codes:

    rhc app create <app name> php-5 postgresql-8 --from-code=https://github.com/openshift-quickstart/tiny_tiny_rss-openshift-quickstart.git

You can now checkout your RSS application at:

    http://<app name>-<your namespace>.rhcloud.com

This app can be shared by multiple users. The default user credential is "admin"/"password".
