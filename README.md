# SatoruBot

Bot de WhatsApp desenvolvido em Node.js utilizando Baileys para automação de mensagens, processamento de mídia e arquitetura modular baseada em eventos.

---

## 📌 Sobre o Projeto

O SatoruBot foi desenvolvido com o objetivo de praticar integração com a API do WhatsApp Web, organização modular de código e processamento de imagens em tempo real.

O projeto implementa conexão persistente, reconexão automática, sistema de middlewares e ações separadas por responsabilidade.

---

## ⚙ Funcionalidades

- Conexão com WhatsApp Web via Baileys
- Autenticação persistente (multi-file auth state)
- Reconexão automática em caso de desconexão
- Sistema de comandos com prefixo
- Middleware central para tratamento de mensagens
- Arquitetura baseada em classes para ações
- Extração de mensagens de múltiplos formatos
- Detecção e download de imagens (inclusive citadas)
- Conversão de imagem para figurinha (.webp) usando FFmpeg
- Limpeza automática de arquivos temporários

---

## 🛠 Tecnologias Utilizadas

- Node.js
- JavaScript
- Baileys (WhatsApp Web API)
- FFmpeg
- child_process
- fs / fs.promises
- Path

---

## 🧠 Conceitos Aplicados

- Programação assíncrona (async/await)
- Arquitetura orientada a eventos
- Separação de responsabilidades
- Manipulação de streams
- Execução de processos externos
- Gerenciamento de sessão persistente
- Middleware pattern

---

## 📂 Estrutura do Projeto

- connect → Gerenciamento de conexão e reconexão
- middlewares → Tratamento central de mensagens
- actions → Classe responsável pelas ações do bot
- utils → Funções auxiliares
- config → Configurações globais
- assets/auth → Armazenamento de sessão

---

## 🚀 Como Executar

1. Instale Node.js
2. Instale FFmpeg na máquina
3. Clone o repositório
4. Instale as dependências:

   npm install

5. Execute:

   node index.js

Escaneie o QR Code no terminal para autenticação.

---

## 🎯 Objetivo

Projeto desenvolvido para consolidar fundamentos de backend com Node.js, integração com APIs externas e processamento de mídia em tempo real.

---

## 📄 Licença

Uso educacional.
