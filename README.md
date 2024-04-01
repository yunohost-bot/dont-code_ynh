<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Dont-code Services for YunoHost

[![Integration level](https://dash.yunohost.org/integration/dont-code.svg)](https://dash.yunohost.org/appci/app/dont-code) ![Working status](https://ci-apps.yunohost.org/ci/badges/dont-code.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/dont-code.maintain.svg)

[![Install Dont-code Services with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=dont-code)

*[Read this README is other languages.](./ALL_README.md)*

> *This package allows you to install Dont-code Services quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Dont-code is a low-code / no-code platform letting user create their own applications based on complete feature sets developed by IT.
You can find more information here: https://dont-code.net

This Yunohost app installs the server part (services + mongo database) needed to run the dont-code applications.

### Features

- Thanks to the Powerful [Builders](https://dont-code.net/ide-ui) and [Previewers](https://dont-code.net/ide-ui), a user can directly design its application and immediately see the result
- One only needs to describe its application by filling sentences prepared by the platform.
- By default it provides support for images, currency, text, numbers, countries, links.
- Multiple plugins allow you to list, edit, make reports, call services, save to database, save in browser, and so on...
- Plugins can be developed by any IT team
- Projects and all user's data are backuped up as part of the Yunohost backup process
- As well any documents or images uploaded by users will be backed up


**Shipped version:** 0.3.1~ynh1

**Demo:** <https://dont-code.net/apps.html>

## Screenshots

![Screenshot of Dont-code Services](./doc/screenshots/previewer.gif)
![Screenshot of Dont-code Services](./doc/screenshots/ide.gif)

## Documentation and resources

- Official app website: <https://dont-code.net>
- Official user documentation: <https://dont-code.net/news.html>
- Official admin documentation: <https://dont-code.net/developers.html>
- Upstream app code repository: <https://github.com/dont-code>
- YunoHost Store: <https://apps.yunohost.org/app/dont-code>
- Report a bug: <https://github.com/YunoHost-Apps/dont-code_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/dont-code_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/dont-code_ynh/tree/testing --debug
or
sudo yunohost app upgrade dont-code -u https://github.com/YunoHost-Apps/dont-code_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
