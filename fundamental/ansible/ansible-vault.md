# Ansible vault
> https://docs.ansible.com/ansible/latest/user_guide/vault.html

## options
```
$ ansible-vault --help
Usage: ansible-vault [create|decrypt|edit|encrypt|encrypt_string|rekey|view] [options] [vaultfile.yml]
encryption/decryption utility for Ansible data files
Options:
  --ask-vault-pass      ask for vault password
  -h, --help            show this help message and exit
  --new-vault-id=NEW_VAULT_ID
                        the new vault identity to use for rekey
  --new-vault-password-file=NEW_VAULT_PASSWORD_FILE
                        new vault password file for rekey
  --vault-id=VAULT_IDS  the vault identity to use
  --vault-password-file=VAULT_PASSWORD_FILES
                        vault password file
  -v, --verbose         verbose mode (-vvv for more, -vvvv to enable
                        connection debugging)
  --version             show program's version number and exit
 See 'ansible-vault <command> --help' for more information on a specific
```
* create / decrypt / edit : 
* encrypt / encrypt_string
* rekey
* view
* --ask-vault-pass
* --vault-id
* --vault-password-file
