#Sobre o Projeto
Este projeto tem como objetivo calcular o tempo necessário para que um investimento inicial atinja o valor de um imóvel específico, levando em consideração o crescimento do investimento por meio de juros compostos anuais. O usuário fornece o valor do imóvel, o investimento inicial e a taxa de juros anual, e o programa calcula quantos anos e meses serão necessários para que o investimento alcance ou ultrapasse o valor do imóvel.

Funcionamento do Projeto
Entrada de Dados:

O programa começa solicitando três valores do usuário:
O valor do imóvel que ele deseja adquirir.
O valor do investimento inicial que ele possui.
A taxa de juros anual (em porcentagem) que o investimento rende.
Viabilidade do Investimento:

O projeto verifica se o investimento inicial é viável, considerando que ele deve ser pelo menos 1% do valor do imóvel. Se o investimento for menor que isso, o programa informa que o investimento é inviável. Caso contrário, o cálculo do tempo é realizado.
Cálculo do Tempo Utilizando Juros Compostos:

A fórmula utilizada para calcular o tempo necessário para atingir o valor do imóvel leva em consideração o crescimento exponencial dos juros compostos. 
 
Aqui, A é o valor final (valor do imóvel), P é o valor inicial (investimento), r é a taxa de juros anual em forma decimal, n é o número de vezes que o juro é aplicado por ano (neste caso, mensalmente), e t é o tempo em anos que será calculado.
Processo de Cálculo:

O programa usa a função math.log() para calcular o tempo necessário, rearranjando a fórmula dos juros compostos para resolver t (tempo). O tempo é inicialmente calculado em anos, e depois é convertido para anos e meses para facilitar a compreensão.
Saída:

O programa exibe a quantidade de anos e meses necessários para que o investimento inicial atinja ou ultrapasse o valor do imóvel, fornecendo ao usuário uma estimativa clara do tempo necessário.# meus-projetos-python