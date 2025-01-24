# Jogo do Número Secreto 🎲

Este é um jogo interativo desenvolvido com HTML, CSS e JavaScript, onde o objetivo é adivinhar um número secreto gerado aleatoriamente pelo programa. Ele também utiliza a API `responsiveVoice` para tornar a experiência mais interativa com feedback de voz.

## 🎮 Como jogar

1. O jogo sorteia um **número secreto** entre 1 e 20 (ou outro intervalo configurado no código).
2. O jogador deve inserir um número no campo de entrada e clicar no botão **"Chutar"**.
3. O jogo fornecerá dicas dizendo se o número secreto é maior ou menor que o chute.
4. Quando o número for descoberto, o jogo exibirá o número de tentativas realizadas.
5. Após acertar, é possível reiniciar o jogo clicando em **"Novo jogo"**.

## 🚀 Funcionalidades

- **Interatividade de voz:** Feedback falado para maior imersão, utilizando a API `responsiveVoice`.
- **Gerador de número único:** Garante que o número secreto não se repita em sequências contínuas até que todos os números do intervalo sejam sorteados.
- **Feedback dinâmico:** Mensagens para guiar o jogador em cada etapa do jogo.
- **Reinício do jogo:** Opção para reiniciar o jogo após acertar o número.

## 📂 Estrutura do Projeto

```plaintext
Raiz do projeto
│
├── index.html          # Estrutura principal do jogo
├── app.js              # Lógica e funcionalidade do jogo
├── style.css           # Estilo visual do jogo
├── /img
│   └── ia.png          # Imagem decorativa usada na interface

