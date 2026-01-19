<h1 align="center">
  Git e GitHub – Hashtag Treinamentos<br>
<img src="https://skillicons.dev/icons?i=git,github" width="65"/>
</h1>

<p align="center">
<img src="img/Hashtag_logo2.jpeg" alt="Hashtag Treinamentos" width="500">
</p>

<p align="center">
  Repositório de estudos baseado no curso de Git & GitHub da<br>
  <strong>Hashtag Treinamentos</strong>, referência em formação prática em programação, automação e análise de dados.
</p>

<p align="center"> 
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=black">
<img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white">
</p>

<h2 align="center">🎯 Objetivo do Repositório: </h2>

<p align="center">
  Este repositório tem como objetivo documentar minha jornada de aprendizado em Git e GitHub,  
  reunindo conceitos fundamentais, comandos essenciais, boas práticas e projetos práticos  
  desenvolvidos ao longo do curso da Hashtag Treinamentos.  
  Aqui também registro anotações, exercícios e aplicações reais de controle de versão e colaboração em projetos. ✅
</p>

<h2 align="center">👨🏻‍💻 Autor deste Repositório: </h2>

<div align="center">

<strong>Lucas Paguetti Pereira</strong> 🥷 <br>
🏫 <strong>Instituição</strong>: Cesar School 🎓🧡  
📍 Recife, Pernambuco — <strong>Brazil</strong> 🇧🇷  

<br>

<a href="https://www.instagram.com/lucpaguetti/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>
<a href="https://github.com/wqiluc">
  <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white">
</a>
<a href="https://www.linkedin.com/in/lucas-paguetti-pereira-70267339b/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a> <br>
<a href="mailto:lpp2@cesar.school">
  <img src="https://img.shields.io/badge/Contact%20Me-lpp2%40cesar.school-FFA500?style=for-the-badge&logo=gmail&logoColor=orange"><br>
</a>
</a>
<a href="https://discord.com/users/lucaspaguettipereira">
  <img src="https://img.shields.io/badge/Discord-lucaspaguettipereira-5865F2?style=for-the-badge&logo=discord&logoColor=blue">
</a>


</div>

<h2 align="center">🌐 Hashtag Treinamentos: </h2>

<div align="center">

<a href="https://www.hashtagtreinamentos.com/">
  <img src="img/Hashtag_logo.jpeg"
       height="28"
       alt="Hashtag Treinamentos">
</a>
<a href="https://www.youtube.com/@HashtagProgramacao">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=black">
</a>
<a href="https://www.instagram.com/hashtagtreinamentos/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
</a>
<a href="https://www.linkedin.com/company/hashtag-treinamentos/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>
</div>

<h2 align="center">⛏️💻 Ferramentas e Tecnologias Utilizadas: </h2>
<div align="center">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" width="40"><br>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=black">
<img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Markdown-FFFFFF?style=for-the-badge&logo=markdown&logoColor=000000">

</div>

<br>

<h1 align="center">Como Baixar e Instalar O Git e O VScode<br>
<img src="https://skillicons.dev/icons?i=git,vscode" width="60"/></h1>

<p>
<strong><img src="https://skillicons.dev/icons?i=git" width="14"/> Baixar e instalar o Git:</strong><br>
• Acesse o site oficial: <a href="https://git-scm.com/">https://git-scm.com/</a><br>
• Clique em "Download" e escolha seu sistema operacional (Windows, macOS, Linux).<br>
• Execute o instalador e siga os passos normalmente.<br>
• Após a instalação, abra o terminal e verifique:<br>
<code>git --version</code>
</p>

<p>
<strong><img src="https://skillicons.dev/icons?i=vscode" width="14"/> Baixar e instalar o VS Code:</strong><br>
• Acesse o site oficial: <a href="https://code.visualstudio.com/">https://code.visualstudio.com/</a><br>
• Clique em "Download" e escolha seu sistema operacional.<br>
• Execute o instalador e siga os passos de instalação.<br>
• Abra o VS Code após a instalação para começar a usar.
</p>



<h1 align="center">
  Comandos do Git 🕹️<br>
  <img src="https://skillicons.dev/icons?i=git" width="25"/>
</h1>

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=dark)](https://conventionalcommits.org)


```bash
site = "https://www.conventionalcommits.org/pt-br/v1.0.0/" 
# Ajuda a entender as mensagens de commit 🖊️

---

git --version (ou v) # Verifica a versão do git na máquina do usuário 💻
git config --global user.name "Seu Nome"
git config --global user.email "email@exemplo.com"
git config --global alias.< sua abreviaçao > funcao original
git config --list
git config --global alias.<sua abreviação> comando original # cria atalhos
git init                  # Inicializa um repositório
git clone <url>           # Clona um repositório 
git remote -v             # Lista repositórios remotos
git remote add origin <url>
git remote remove origin <nome>
git status                # Mostra arquivos 
git log                   # Mostra histórico 
git log --oneline         # Log resumido
git log --graph --all     # Gráfico de commits
git show <hash>           # Detalhes de um commit 
git add <arquivo>         # Adiciona arquivos ao 
git add .                 # Adiciona todos os arquivos
git commit -m "Mensagem"  # Commit com mensagem
git commit -am "Mensagem" # Comita alterações 
git commit --amend         # Edita o último commit
git branch                # Lista branches locais
git branch <nome>         # Cria uma nova branch
git push -u origin minha-branch    # envia a branch 'minha-branch' para o remoto 'origin'
git checkout <nome>       # Muda para outra branch
git checkout -b <nome>    # Cria e muda para nova 
git merge <branch>        # Faz merge de outra branch
git merge feature-login
git branch -d <nome>      # Deleta branch local
git branch -D <nome>      # Força a deletar branch 
git push origin --delete <branch>  # Deleta branch 
git fetch                 # Baixa commits remotos sem 
git pull                  # Baixa e faz merge 
git push                  # Envia commits locais para 
git push -u origin <branch>  # Define upstream
git reset --soft <hash>   # Reseta HEAD, mantém 
git reset --mixed <hash>  # Reseta HEAD, mantém 
git reset --hard <hash>   # Reseta HEAD e descarta 
git revert <hash>         # Cria commit que desfaz 
git rebase <branch>       # Reaplica commits sobre 
git rebase --continue
git rebase --abort
git cherry-pick <hash>    # Aplica commit específico 
touch .gitignore
echo "node_modules/" >> .gitignore
git status --ignored      # Ver arquivos ignorados
git stash                 # Salva alterações 
git stash list            # Lista stashes
git stash apply           # Aplica último stash
git stash pop             # Aplica e remove stash da 
git stash clear           # Remove todos os stashes
git reflog                # Mostra histórico de HEADs e mudanças
git blame <arquivo>       # Mostra linha por linha quem alterou
git bisect start
git bisect good <hash>    # Commit sem bug
git bisect bad             # Commit com bug
git bisect reset           # Finaliza bisect

      # ===================== 🔖 TODOS OS COMANDOS DE GIT TAG =====================
      
git tag                                               # lista todas as tags locais
git tag -l "v1.*"                                    # lista tags filtrando por padrão

git tag v1.0.0                                       # cria uma tag leve (lightweight)
git tag -a v1.0.0 -m "Primeira versão estáável"     # cria uma tag anotada (recomendada)

git tag v1.0.0 <commit-hash>                        # cria uma tag leve em um commit específico
git tag -a v1.0.0 <commit-hash> -m "msg"           # cria uma tag anotada em um commit específico

git show v1.0.0                                     # mostra detalhes da tag e do commit associado

git tag -d v1.0.0                                   # apaga uma tag local
git push origin --delete v1.0.0                     # apaga a tag no GitHub (remoto)

git push origin v1.0.0                              # envia uma tag específica para o GitHub
git push --tags                                     # envia todas as tags locais para o GitHub

git tag v2.0.0 v1.0.0                               # cria nova tag apontando para o mesmo commit (forma de “renomear”)
git tag -d v1.0.0                                   # apaga a tag antiga localmente
git push origin --delete v1.0.0                     # apaga a tag antiga no remoto
git push origin v2.0.0                              # envia a nova tag para o remoto

git tag -s v1.0.0 -m "Release assinada"            # cria uma tag assinada com GPG

git rev-parse v1.0.0                                # mostra o hash do commit apontado pela tag

git log --oneline --decorate --tags                 # mostra histórico com tags associadas aos commits

git tag --contains <commit-hash>                    # mostra quais tags contêm esse commit

git tag -n                                          # lista tags mostrando também a mensagem das tags anotadas
git tag -n3                                         # mostra até 3 linhas da mensagem de cada tag

git tag -f v1.0.0 <commit-hash>                    # força a recriação de uma tag existente em outro commit

git push origin :refs/tags/v1.0.0                  # outra forma de deletar tag no remoto

                # ===================== RESUMO RÁPIDO ===================== #

git tag -a v1.0.0 -m "Release"                     # criar tag recomendada
git push origin v1.0.0                             # enviar tag para GitHub
git show v1.0.0                                    # visualizar tag
