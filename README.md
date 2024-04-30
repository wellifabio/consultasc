# Projeto: Consultas com Nutricionista

Resolução de uma atividade (Situação Problema) com linguagem C

## Conhecimentos
- Lógica de programação estrutural
- Vetores **[]**
- Estruturas **struct**
- Funções e procedimentos
- Resolução de problemas
- Requisitos e modelagem de dados
- UML - Diagrama de Casos de Uso

### Contextualização
O consultório da nutricionista Dra. Ângela Maria necessita de um sistema de agendamento de consultas, você como programador e empreendedor pretende prestar este serviço como PJ

## Documento de Requisitos Programa de Agendamento de Consultas
O documento deste projeto consiste na descrição de cada requisito separado por funcionais e não funcionais, proridade de desenvolvimento (Essencial, Importante e Desejável) e uma ilustração através de Diagramas de Casos de Uso da UML ()
### Requisitos
|Não Funcionais|Prioridade|
|:-:|-|
|[<img src="https://images.sftcdn.net/images/t_app-icon-m/p/4095d654-96d0-11e6-87f8-00163ed833e7/1965154745/bloodshed-dev-c-icon.jpg" style="width:50px">](https://www.bloodshed.net/)RN001 - Linguagem C|_Essencial_|
|RN002 - Programação estrutural e funcional|_Essencial_|

|Funcionais|Prioridade|
|:-:|-|
|RF001 - Cadastro de **Pacientes** com os campos (CPF, nomeCompleto, telefone)<br>![DCU01](./dcu01.png)|_Essencial_|
|RF002 - Cadastro de **Consultas** contemplando os campos (data, hora, paciente, nomeAtendente)<br>![DCU02](./dcu02.png)|_Essencial_|
|RF003 - Cancelar/Excluir consulta<br>![DCU03](./dcu03.png)|_Importante_|
|RF004 - Alterar data e horário da consulta<br>![DCU04](./dcu04.png)|_Desejável_|
|RF005 - Criar menu com todas estas opções e a opção de Sair<br>![DCU05](./dcu05.png)|_Essencial_|

|OBS:|
|-|
|Não é necessário realizar a persistência de dados, pois o sistema será implantado em uma VM em Núvem com disponibilidade de 24horas|

### Para testar
- 1 Fazer downoad deste repositório
- 2 Executar o código consultas.c com compilador C **DevC++**

## Resultados (Testes unitários)
|Requisito|Evidência|
|-|:-:|
|RF001<br>RF005|![Tela01](./tela01.png)|
|RF001.1|![Tela01b](./tela01b.png)|
|RF001|![Tela02](./tela02.png)|
|RF002|![Tela03](./tela03.png)|
|RF002|![Tela04](./tela04.png)|
|RF003|![Tela06](./tela05.png)|
|RF004|![Tela06](./tela06.png)|
