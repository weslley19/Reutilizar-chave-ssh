# Reutilizar chave SSH no Linux 

- Digite os seguintes comando no terminal:

<!-- Ativar o agente ssh -->
eval "$(ssh-agent -s)"

<!-- Alterar permissão da chave privada -->
chmod 600 ~/.ssh/id_rsa

<!-- Adicionar chave ao agente -->
ssh-add ~/.ssh/id_ed25519
