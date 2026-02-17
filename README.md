# ConnectionTaxi
**ConnectionTaxi** é um sistema de táxi voltado para regiões locais com pouco acesso a profissionais de transporte, oferecendo uma solução prática para conectar motoristas e passageiros em áreas afastadas e com baixa disponibilidade de contatos.

# 📌 Visão Geral
Este projeto foi criado para facilitar a conexão e o gerenciamento de corridas de táxi em regiões onde há pouca disponibilidade de transporte local e o contato com motoristas nem sempre é fácil. A aplicação foi desenvolvida em **TypeScript** e utiliza uma arquitetura de backend escalável, preparada para crescimento e futuras integrações.

# 🚀 Funcionalidades:

# 🧱 Tecnologias Utilizadas
O projeto foi desenvolvido com as seguintes tecnologias:

### Backend
- **TypeScript** — Linguagem principal do projeto.
- **Node.js** — Ambiente de execução.
- **Express** — Framework para a criação de APIs REST e etc...
- **JWT** — *Json_Web_Token* para autênticação e autorização.
- **Bcrypt** — Criptografia de senhas.
- **Cookie-Parser** — Cookies.
- **Nodemailer** — Biblioteca Node.js para envios de mensagens por email.
- **Nodemon** — Utilitário de interface de linha de comando (CLI) para Node.js que aprimora o fluxo de trabalho de desenvolvimento.
- **Cors** — Compartilhamento de Recursos entre Origens.
- **Pg** — Node-postgres, para usar PostgreSQL no Node.js.

#### Banco de dados
- **Postgres** — Banco de dados relacional que será usado para armazenar os dados.
  
#### Api Test
- **Postman** — Testes de Apis e etc...

### Frontend
- **React.js + Vite** — Biblioteca para criação de interfaces e fazer componetização
- **Tailwind** — Framework do css para estilização

# 🗂 Estrutura do Projeto

```
backend/
├─ src/
│  ├─ core/
│  │  ├─ errors/
│  │  ├─ ports/
│  │  └─ usercases/
│  ├─ infra/
│  │  ├─ database/
│  │  │  ├─ connection/
│  │  │  └─ model/
│  │  ├─ providers/
│  │  └─ repository/
│  ├─ interface/
│  │  ├─ controllers/
│  │  ├─ middlewares/
│  │  ├─ routes/
│  │  └─ validators/
│  └─ main/
│     └─ server.ts
└─ .env
```
