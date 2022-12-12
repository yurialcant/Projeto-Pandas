# Projeto Pandas Alura
| 🪧 Vitrine.Dev |     |
| -------------  | --- |
| ✨ Nome        | Projeto-Pandas-Alura
| 🏷️ Tecnologias | Python, Pandas, matplotlib
| 🚀 URL         | https://github.com/yurialcant/Projeto-Pandas-Alura
| 🤿 Desafio |https://cursos.alura.com.br/course/introducao-python-pandas

<h1 align ="center"> Introdução á biblioteca Pandas do Python </h1>
<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=%20COMPLETO&color=GREEN&style=for-the-badge"/>
</p>

![](https://user-images.githubusercontent.com/102321564/194167852-79896f47-325d-4c14-a754-07e75568bdd9.png#vitrinedev)

Este projeto foi criado durante o curso de introdução á biblioteca Pandas do Python, pertencente a formação Data Science, neste curso aprendemos a usar o básico da biblioteca,
como funções, ler e escrever um arquivo csv e realizar o tratamento de dados, entre outras funções, aprendemos também a manipular a biblioteca matplotlib para gerar gráficos

<h1 align ="center"> Resultados Obtidos </h1>
Em nosso projeto, realizamos ele em etapas, formando assim diversos relatórios de análise de nossos dados.

<h1> Relatório de Análise I </h1>
<h2> Importando a Base de Dados & Informações Gerais sobre a Base de Dados</h2>
Em nosso primeiro relatório de dados aprendemos a abrir e realizar a leitura de um arquivo csv, através do "read_csv",
especificando o caminho do arquivo e o separador necessário para realizar a leitura, e aprendemos a visualizar nosso dados, como um Data Frame.

![Captura de Tela (190)](https://user-images.githubusercontent.com/102321564/194167852-79896f47-325d-4c14-a754-07e75568bdd9.png)

Em seguida aprendemos a visualizar as informaçãos gerais, como o tipo de nossos dados e a quantidade de registro.

![Captura de Tela (191)](https://user-images.githubusercontent.com/102321564/194168132-cf9504b2-a021-43fc-837f-ac8e7daeb2c6.png)

<h1> Relatório de Análise II </h1>
<h2> Tipos de Imóveis & Organizando a visualização </h2>
Em nosso segundo relatório, primeiro aprendemos a revomer entradas duplicadas da nossa base de dados através do comando "drop_duplicates" colocando o parâmetro inplace = True, para que as mudanças realizadas sejam aplicadas no nosso DataFrame,

![Captura de Tela (192)](https://user-images.githubusercontent.com/102321564/194169092-e5e0ee1e-1022-4003-aa9a-6c85d6843658.png)

Após isso, organizamos a visualização dos nossos Dados, criando e organizando a tabela de Ids, dos nossos tipos de imóveis.

![Captura de Tela (193)](https://user-images.githubusercontent.com/102321564/194169611-76ab3e5d-b6d2-4c29-9810-94efd5712982.png)

<h1> Relatório de Análise III </h1>
<h2> Separando os Imóveis Residenciais & Exportando a Base de Dados </h2>
No nosso terceiro relatório, optamos primeiro por fazer uma seleção somente dos imóveis residencais, pra gerar uma nova Base de dados somente com esse grupo, portanto criamos a variável seleção que recebe nossos dados com a função issin, após isso podemos atribuir uma nova base de dados, somente com os imóveis do tipo residencial.

![Captura de Tela (194)](https://user-images.githubusercontent.com/102321564/194170616-e6119388-c8e9-46d3-bed2-af60fc1dfb70.png)

Com isso feito, podemos exportar essa nova base de dados para um novo arquivo csv.

![Captura de Tela (195)](https://user-images.githubusercontent.com/102321564/194170881-50c8ac44-8b7c-48d8-ac14-7dc4af3036ea.png)

<h1> Relatório de Análise IV </h1>
<h2> Criando Novas Variáveis & Excluindo Variáveis </h2>
No quarto relatório aprendemos a forma básica de se adicionar variáveis na nossa base de dados, conseguindo criar variáveis com operações matemáticas, envolvendo outras variáveis, já presentes na base de dados.

![Captura de Tela (196)](https://user-images.githubusercontent.com/102321564/194171719-f4f71963-1b81-4aa3-a8f3-d1a4717ec486.png)

Logo em seguida, aprendemos as funções básicas para excluir variáveis da base de dados.

![Captura de Tela (197)](https://user-images.githubusercontent.com/102321564/194171994-158de275-99c3-43f8-8789-7fa917b139a7.png)

<h1> Relatório de Análise V </h1>
<h2> Tratamento de Dados Faltantes</h2>
Nesta estapa, aprendemos a tratar nossa base de dados, como possuímos alguns dados constando como "NaN", aprendemos a substituir esses dados faltantes para montarmos um DataFrame completo sem esses elementos faltantes.

![Captura de Tela (198)](https://user-images.githubusercontent.com/102321564/194172872-9aeea2cc-2b7b-484c-963a-e9ed725b9faa.png)

![Captura de Tela (199)](https://user-images.githubusercontent.com/102321564/194172898-afda8afb-4c3c-49d7-9394-57d0bee058cc.png)

<h1> Relatório de Análise VI </h1>
<h2> Criando Agrupamentos & Estatísticas Descritivas </h2>
Neste relatório, aprendemos a criar agrupamentos, selecionando alguns imóveis de determinado bairros e criando um novo DataFrame, destes imóveis com a média do valor e condominio por bairro.

![Captura de Tela (200)](https://user-images.githubusercontent.com/102321564/194173613-639733ba-a131-4d8a-822c-ff4deeb069b5.png)

Após isso, começamos a utilizar a biblioteca matplotlib do Python, para passar esta base de dados para um gráfico de barro, utilizando a média para construir as informações de nossos gráficos.

![Captura de Tela (201)](https://user-images.githubusercontent.com/102321564/194174221-95565804-0f38-4b7a-90ef-dd32e163d4ed.png)

<h1> Relatório de Análise VII </h1>
<h2> Identificando e Removendo Outliers </h2>
Neste relatório continuamos a utilizar a biblioteca pandas em conjunto com a matplotlib, para gerarmos um gráfico do tipo Box-Plot, para isso precisamos remover os outliers (dados que se diferenciam drasticamente de todos os outros) de nossa base de dados, para isso criamos um limite com base no valor do imóvel e com isso prosseguimos para a fórmula do nosso gráfico.

![Captura de Tela (202)](https://user-images.githubusercontent.com/102321564/194175069-4d76ed7b-3695-49b5-afeb-289438634b4d.png)

Após isso, agrupamos nossos tipos de imóveis, refizemos a fórmula e criamos um Box-Plot para cada tipo de imóvel na nossa basse de dados.

![Captura de Tela (203)](https://user-images.githubusercontent.com/102321564/194175465-475c1b4e-fb62-4b72-843a-715214ba3d30.png)

Com isso exportamos nossa nova base de dados, desta vez sem os Outliers e concluímos o projeto.



