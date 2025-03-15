Vector-role
=========

Ansible role for installing and configuring Vector on an RHEL server

Requirements
------------

- ansible 2.17.8

Role Variables
--------------

`vector_version`: The version of Vector to be installed. Default: "0.45.0".

Example Playbook
----------------

    - hosts: servers
      roles:
         - vector-role

License
-------

MIT

Author Information
------------------

If you have any questions or suggestions for improving this Playbook, please create an issue in the repository.
