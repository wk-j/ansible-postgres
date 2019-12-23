## Hello

```bash
ansible -m shell -a 'whoami' all
```

## Playbook

```bash
ansible-playbook playbook.yml

ufw allow 5432/tcp
ufw allow 80/tcp
ufw allow 8000/tcp

psql -h 165.22.106.25 -U wk -d wk -W
```

## Resource

- https://blog.apcelent.com/using-ansible-to-set-up-postgresql.html