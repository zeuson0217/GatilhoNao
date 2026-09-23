# Gatilho Não

Código-fonte da versão publicada do projeto.

## Arquivos

- `index.html`: interface, estilos e funcionamento do aplicativo.
- `firestore.rules`: regras de segurança para o banco de dados Firebase.
- `.openai/hosting.json`: configuração da publicação do site.

## Configuração necessária no Firebase

1. Adicione `gatilho-nao.milenanicolayn.chatgpt.site` aos domínios autorizados do Firebase Authentication.
2. Publique o conteúdo de `firestore.rules` nas regras do Cloud Firestore.
3. Confirme que o login com Google está habilitado em Authentication > Sign-in method.

O arquivo `index.html` já contém a configuração Firebase usada no código original enviado para o projeto.

