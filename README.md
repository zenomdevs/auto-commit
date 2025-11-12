## 🚀 Upload Automático

Um script simples e divertido para enviar pastas do **Termux** para o GitHub automaticamente!  

Perfeito para versionar projetos rapidamente sem complicação.

---

## 📝 Descrição

Este script faz tudo por você:

1. 💻 Verifica se o **Git** está instalado e instala se necessário.  
2. 📂 Inicializa o repositório (`git init`) caso ainda não exista.  
3. 🔒 Configura o diretório como seguro (`safe.directory`).  
4. ✏️ Configura usuário e e-mail do Git (opcional).  
5. ➕ Adiciona todos os arquivos e realiza um commit automático.  
6. 🔑 Pede seu **Personal Access Token** do GitHub na hora do push.  
7. 🚀 Envia os arquivos para a branch principal (`main` por padrão).  

---

## ⚡ Requisitos

- Termux no Android  
- Git instalado (`pkg install git`)  
- Token no GitHub  
- [Access Token](https://github.com/settings/tokens) com permissão `repo`  
---
## 🤖 Configure o user/repo
---
1. Baixe ou clone o script `upload.sh` na pasta do seu projeto.  
---
2. Abra o Termux e acesse sua pasta:
```
cd /sdcard/caminho/da/pasta
```
---
3. Depois de configurar user/repo:
```
sh upload.sh
```
---
5. Vai pedir o seu token, você coloca.
---
6. Aparecerá a mensagem de concluído e seu projeto já vai estar no GitHub.
---

## ✅️ Processo concluído!
