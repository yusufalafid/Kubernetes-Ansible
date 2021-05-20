### Kubernetes ansible

Kubernetes deployment tools

Prerequisite

1. Install Ansible

```
sudo apt install ansible
```

2. Clone Repository
3. Install ansible posix module

```
ansible-galaxy collection install ansible.posix
```

4. Change Kubernetes version on group_vars
5. Change inventory
6. Run playbooks
```
ansible-playbook -i hosts/hosts main.yml
```