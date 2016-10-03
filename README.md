# Ansible Role - PostgreSQL

[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/wolffaxn/ansible-role-postgresql/master/LICENSE)

Installs PostgreSQL for RedHat/CentOS linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values:

## Dependencies

None.

## Example Playbook

For RHEL / CentOS

```yaml
---
- hosts: localhost
  become: true
  become_method: sudo
  remote_user: root
  roles:
    - ansible-role-postgresql
```
## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

This role was created by Alexander Wolff.
