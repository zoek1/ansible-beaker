[![Stories in Ready](https://badge.waffle.io/zoek1/ansible-beaker.png?label=ready&title=Ready)](https://waffle.io/zoek1/ansible-beaker)
ansible-beaker
==============

Install Beaker

configuration
-------------

Add your ip in file *host*:

```ini
[beaker]
yourip.io
```

Usage
-----

Install beaker is very easy:

```console
$ ansible-playbook site.yml -i hosts
```

License
-------

Docker is licensed under the GNU GPL v3 License. See LICENSE for full license text.
