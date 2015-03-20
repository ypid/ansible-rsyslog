## service-rsyslog

[![Travis CI](http://img.shields.io/travis/ypid/ansible-service-rsyslog.svg?style=flat)](http://travis-ci.org/ypid/ansible-service-rsyslog)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-ypid.service–rsyslog-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2767)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)


My rsyslog configuration. Reconfigures log format and to which files to log.

An example logline locks like this:

    <syslog.info>1 Feb  1 18:59:31 mix-uno rsyslogd - - -  [origin software="rsyslogd" swVersion="8.4.2" x-pid="5870" x-info="http://www.rsyslog.com"] start

The log format is based on [RFC 3164](http://www.ietf.org/rfc/rfc3164.txt) with some modifications to make it easier readable for humans.

This role also changes some logrotate defaults.

### Installation

This role requires at least Ansible `v1.2`. To install it, run:

    ansible-galaxy install ypid.service-rsyslog

To install via git, run either:

    git clone https://github.com/ypid/ansible-service-rsyslog ypid.service-rsyslog
    git submodule add https://github.com/ypid/ansible-service-rsyslog roles/ypid.service-rsyslog







### Authors and license

`service-rsyslog` role was written by:

- [Robin Schneider](https://github.com/ypid) | [e-mail](mailto:ypid@riseup.net)

License: [AGPLv3](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-%28agpl-3.0%29)

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
