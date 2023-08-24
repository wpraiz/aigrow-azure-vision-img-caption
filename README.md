Repositório de Análise de Imagens em Lote com Azure AI Vision

Este repositório contém um script em Python que utiliza o Azure AI Vision SDK para analisar um conjunto de imagens em lote. O script carrega imagens de um diretório, realiza análises em cada imagem usando a função 'image_analysis_sample_analyze' e armazena os resultados em um dataframe do pandas. Os resultados incluem o caminho da imagem, legenda e legendas detalhadas. É necessário ter instalado o Azure AI Vision SDK para Python e um arquivo de segredos com o endpoint e chave para o serviço Azure.

Recursos:
- Carregamento e análise de imagens em lote usando Azure AI Vision
- Geração de legendas e legendas detalhadas para cada imagem
- Armazenamento dos resultados em um dataframe do pandas

Instruções de Uso:
1. Instale as dependências listadas no README.md.
2. Configure suas credenciais no arquivo load_secrets.py.
3. Coloque as imagens a serem analisadas no diretório especificado.
4. Execute o script para realizar a análise em lote.

Lembre-se de não compartilhar informações sensíveis ou credenciais no repositório.

Este projeto é desenvolvido para fins educacionais e de demonstração de uso do Azure AI Vision SDK com Python.
