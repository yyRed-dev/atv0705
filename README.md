# atv0705

Implementar um servidor REST na linguagem Node.js e testar a invocação de
requisições GET através de um cliente implementado em outra linguagem (no caso
Java).

Objetivos:
● Criar um serviço REST no Node.js e subir o mesmo no GitHub
● Fazer o deploy do serviço REST na nuvem AWS
● Testar o serviço com requisições GET no Browser
● Criar um Cliente que irá consumir o serviço REST em uma aplicação Java
● Testar o cliente rodando na máquina localmente

Passo 1 - Implementar a aplicação servidora como um serviço REST no Node.js. OBS: Pode se
basear no tutorial anterior sobre deploy de aplicação node na AWS.
1.1. Baixe os arquivos disponíveis no AVA (Serviço REST - Servidor - Node.js e users.json) e
suba os dois arquivos em um repositório novo no Github.
1.2. Crie uma VM na AWS e configure o projeto Node.js para usar o pacote express fazendo o
clone do github. Os arquivos devem estar na mesma pasta. S
1.2.1. Inicializar o projeto - npm init
1.2.2. Instalar o express - npm install express --save
1.2.3. Configurar o projeto no VSCode
1.2.4. Rodar a aplicação
1.3. Testar no browser para as rotas GET definidas com o IP gerado pela AWS.

Passo 2 - Implementar a aplicação cliente REST no Java
2.1. Baixe o arquivo (Cliente REST - Aplicação Java) e configure um projeto Java no seu
ambiente de preferência (Ex: Eclipse).
2.2. Compile a aplicação e Execute a mesma.
2.3. Observe se o resultado no console retorna as mesmas informações que a requisição do
Browser.