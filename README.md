# Contajá - Full Stack Web Developer - Laravel

O projeto proposto nesse desafio tem como objetivo avaliar os candidatos a Full Stack Web Developer na Contajá.

## Sobre nós
A Contajá oferece uma solução simplificada, eficiente e ágil, resolvendo problemas complexos para uma geração acostumada com tecnologia.

## Espeficiações Técnicas

- Frontend: Vue.js (podem ser utilizados frameworks de UI à sua escolha)
- API: PHP com Laravel
- Banco de Dados: MySQL

Justifique as tecnologias que você escolheu utilizar além das especificadas.

## A aplicação

Você deverá criar uma aplicação chamada "Eventosjá", que irá permitir aos usuários criar e gerenciar seus eventos.

## Premissas

* Considere que o usuário está logado como administrador do sistema, não é necessária uma interface de login.

## Interfaces

**A aplicação é composta por quatro telas:**
* a lista de eventos
* a lista dos convidados de um evento
* a inclusão de um evento
* a inclusão de um convite

**A lista de eventos**
* Existe uma lista de eventos cadastrados
* Existe um botão para incluir um novo evento
* Existe, para cada evento, um botão para editar
* Existe, para cada evento, um botão para excluir
* Existe, para cada evento, um botão para acessar a lista de convidados

**A lista de convidados**
* Existe uma lista de convidados
* Existe um botão para incluir um novo convidado
* Existe, para cada convidado, um botão para excluir

**A inclusão de um evento**
* Existe um formulário com os campos obrigatórios:
  - Descrição
  - Data do Evento
* Existe um botão para salvar
* Existe um botão para cancelar

**A inclusão de um convidado**
* Existe um formulário com os campos obrigatórios:
  - Nome
  - E-mail
  - Confirmação do E-mail
* Existe um botão para salvar
* Existe um botão para cancelar

### Validações

* Não é permitido incluir mais de um evento por dia
* Não é permitido editar a data de um evento que possui convidados
* Não é permitido excluir um evento que possui convidados
* Não é permitido editar o e-mail de um convidado

Comunique, sempre que possível, ao usuário o motivo de não ser possível executar as operações.

## Critérios de Avaliação

Avaliaremos seu projeto como um produto pronto para produção, porém, que continuará em evolução recebendo novas features.

Registre tudo neste repositório: suas ideias, tentativas e principalmente toda as instruções para instalar e executar seu projeto. Não é necessário o deploy do projeto.

A avaliação será focada nos seguintes itens:

- se atende a todos os requisitos básicos descritos neste documento
- a usabilidade
- a aplicação de boas práticas a nível de código, arquitetura e tomada de decisões
- o versionamento do código e a utilização de boas mensagens de commit

## Considerações finais

Faça um arquivo com as instruções para executar seu projeto, sugerimos o nome INSTRUCTIONS.md

Utilize o projeto para mostrar o seu melhor, deixe registrado todas as suas intenções e boa sorte!