# Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX 

O objetivo destina-se a utilizar uma tabela única de **Amostra Financeira** para criar um modelo baseado em **esquema estrela**, que incluem tabelas de dimensão e fato. O processo envolve uma criação de novas tabelas a partir da tabela original, selecionando colunas específicas para compor uma visão das novas tabelas. Assim, uma tabela principal (fato) será utilizada para gerar como tabelas de dimensão.

## Estrutura das Tabelas

- **F_Vendas** (fato)
- **D_Produtos** (dimensão)
- **D_Produtos_Detalhes** (dimensão)
- **D_Detalhes** (dimensão)
- **D_Calendário** (dimensão)

## Descrição dos Passos Utilizados

1. **Importação de Dados**  
 Importar os dados da planilha **Amostra Financeira** para o **Área de trabalho Power BI**.

2. **Duplicação da Tabela**  
 Duplicar a tabela **Finanças** e criar uma tabela **Financials_origem** (backup).

3. **Criação da Tabela Fato**  
 Na Modelagem, criar a tabela **F_Vendas** (fato).

4. **Criação das Tabelas de Dimensão**  
 Criar as seguintes tabelas de dimensão:
   - **D_Produtos**
   - **D_Produtos_Detalhes**
   - **D_Detalhes**
   - **D_Descontos**
   - **D_Calendário**  
   *(construída conforme orientações de "Os Primeiros Passos com DAX")*

5. **Transformação e Definição de Colunas**  
 Realizar uma transformação, composição e definição das colunas para como tabelas de dimensão: **D_Produtos**, **D_Produtos_Detalhes**, **D_Descontos**, e **D_Detalhes**.

6. **Organização e Relações**  
 Organizar, estabelecer links e definir os relacionamentos entre como tabelas conformes o **Esquema Estrela**.
