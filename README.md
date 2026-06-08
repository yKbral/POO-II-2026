# Sistema de Gerenciamento de Pedidos da Cafeteria

Autor: Caio Emmanuel de Araújo Cabral

## Descrição

Aplicação em Java para gerenciar clientes, produtos, pedidos e itens de pedido via console.

## Arquivos

- `Cliente.java`
- `Produto.java`
- `Pedido.java`
- `ItemPedido.java`
- `Main.java`

## Como compilar

No diretório do projeto, execute:

```bash
javac *.java
```

## Como executar

```bash
java Main
```

## Fluxo de teste simples

1. Cadastrar cliente
   - Opção `1`
   - Nome: `Caio Emmanuel`
   - Telefone: `11999999999`

2. Listar clientes
   - Opção `2`

3. Cadastrar produto
   - Opção `5`
   - Nome: `Café`
   - Preço: `4.50`

4. Listar produtos
   - Opção `6`

5. Criar pedido
   - Opção `9`
   - ID do cliente: `1`

6. Adicionar item ao pedido
   - Opção `13`
   - ID do pedido: `1`
   - ID do produto: `1`
   - Quantidade: `2`

7. Listar pedidos
   - Opção `10`

8. Calcular total do pedido
   - Opção `16`
   - ID do pedido: `1`

9. Sair
   - Opção `0`

## Resultado esperado

- O cliente deve ser cadastrado sem nome vazio.
- O produto deve ser cadastrado com preço maior que zero.
- O pedido deve estar associado ao cliente existente.
- O item deve ser adicionado ao pedido com quantidade maior que zero.
- O total do pedido deve ser calculado corretamente.

## Observação

Se o comando `javac` não estiver disponível, instale o JDK antes de compilar e executar o projeto.


