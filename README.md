📊 Projeto de Análise de Dados: Performance de Vendas (Rede de Lojas)
Este projeto consiste numa análise exploratória de dados (EDA) automatizada para uma rede de 4 lojas. O objetivo é consolidar informações de diferentes fontes (arquivos CSV), extrair métricas de desempenho e gerar visualizações que facilitem a tomada de decisões estratégicas.

📋 Funcionalidades
O código desenvolvido realiza as seguintes etapas:

Extração e Consolidação: Leitura e unificação de múltiplos arquivos CSV (loja_1.csv a loja_4.csv).

Análise de Faturamento: Cálculo da receita bruta por unidade.

Mix de Produtos: Identificação das categorias mais vendidas e dos produtos com maior/menor saída.

Satisfação do Cliente: Cálculo da média de avaliações por loja.

Análise Logística: Estudo do custo médio de frete e sua relação com o preço dos produtos.

Performance de Vendas: Ranking dos melhores vendedores por faturamento.

Visualização de Dados: Geração de gráficos de barras, pizza, linha e dispersão.

🛠️ Tecnologias Utilizadas
Python 3.12

Pandas: Manipulação e tratamento de dados.

Matplotlib: Criação de visualizações gráficas.

Google Colab: Ambiente de desenvolvimento em nuvem.

🚀 Como Executar o Projeto
Abra o Google Colab.

Crie um novo Notebook.

Faça o upload dos arquivos loja_1.csv, loja_2.csv, loja_3.csv e loja_4.csv para a área de arquivos lateral.

Copie e execute as células de código conforme organizado nas etapas de análise.

📈 Insights Obtidos
Através dos gráficos gerados, identificamos:

A Loja 1 detém o maior faturamento da rede.

As categorias de Móveis e Eletrónicos representam quase 50% do volume de vendas.

Existe uma correlação direta entre o preço do produto e o custo de transporte (frete).

A média de satisfação dos clientes é estável em todas as unidades, mantendo-se próxima de 4.0/5.0.

📁 Estrutura dos Arquivos de Dados
Os arquivos CSV devem conter as seguintes colunas:

Produto: Nome do item vendido.

Categoria do Produto: Segmento do item.

Preço: Valor de venda.

Frete: Valor do transporte.

Data da Compra: Data no formato DD/MM/AAAA.

Vendedor: Nome do funcionário.

Avaliação da compra: Nota de 1 a 5.
