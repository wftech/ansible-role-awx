AWX
=========

Role install ansible awx locally on server.

Requirements
------------

docker: https://github.com/VerosK/ansible-role-docker.git
ansible: https://github.com/davidkarban/ansible-role-ansible.git 


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: davidkarban.awx }

License
-------

Apache 2.0
