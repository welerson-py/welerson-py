<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1b3a,50:16305c,100:2f55a4&height=190&section=header&text=Welerson%20dos%20Anjos&fontColor=ffffff&fontSize=46&fontAlignY=36&desc=Backend%20Developer%20%C2%B7%20LLM%20Security&descAlignY=58&descSize=18" width="100%"/>

<a href="https://github.com/welerson-py">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&pause=1200&color=5B9CFF&center=true&vCenter=true&width=620&lines=Python+%C2%B7+FastAPI+%C2%B7+PostgreSQL;RAG%2C+LLMs+locais+e+seguran%C3%A7a+de+modelo;1.200+experimentos.+Zero+GPU.;Pesquisa+publicada+com+c%C3%B3digo+e+dados+abertos" alt="typing"/>
</a>

<br/>

<a href="https://www.linkedin.com/in/welersondosanjos"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://huggingface.co/apollowmm"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/></a>
<a href="https://doi.org/10.5281/zenodo.22861168"><img src="https://img.shields.io/badge/DOI-10.5281%2Fzenodo.22861168-1f4e9c?style=for-the-badge&logo=doi&logoColor=white"/></a>
<a href="mailto:welerson.anjos1@hotmail.com"><img src="https://img.shields.io/badge/E--mail-D44638?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<img src="https://komarev.com/ghpvc/?username=welerson-py&style=flat-square&color=2f55a4&label=visitas"/>
<img src="https://img.shields.io/github/followers/welerson-py?style=flat-square&color=2f55a4&label=seguidores"/>

</div>

<br/>

<div align="center">

### 📄 Pesquisa publicada

</div>

> ### [Does Language Resource Level Change Prompt Injection Success in Offline RAG?](https://www.incbac.org/unigou-proceedings/?article_id=919)
>
> **UNIGOU Proceedings — INCBAC**, Instituto de Cooperação Acadêmica Brasil–Chéquia · 2026
>
> Desenhei e executei um experimento de **1.200 testes** sobre prompt injection indireta em
> sistemas RAG, em **20 idiomas**, **7 sistemas de escrita** e **3 modelos de peso aberto** —
> inteiramente em CPU, sem GPU nenhuma.
>
> O achado é contraintuitivo: o ataque funciona **menos** em idiomas de baixo recurso, caindo de
> 60% para 9,5% na classe de payload imune a erro de medição. **Mas isso não é segurança.** O
> modelo falha em entender o ataque e a pergunta do usuário igualmente — sem atacante nenhum,
> **30% das respostas vinham sem fundamento no documento**, a 5 ou 6 vezes o custo de compute.
>
> Durante a análise encontrei **quatro defeitos na minha própria instrumentação**, e os quatro
> favoreciam a minha hipótese. Corrigi, o resultado ficou mais fraco, e foi esse que publiquei —
> com as 1.200 gerações brutas abertas, pra qualquer um discordar da minha pontuação com dado.

<div align="center">

[![Artigo](https://img.shields.io/badge/📘_Artigo-16305c?style=for-the-badge)](https://www.incbac.org/unigou-proceedings/?article_id=919)
[![Código](https://img.shields.io/badge/💻_C%C3%B3digo-16305c?style=for-the-badge)](https://github.com/welerson-py/RAGSEC)
[![Dataset](https://img.shields.io/badge/📊_Dataset-16305c?style=for-the-badge)](https://huggingface.co/datasets/apollowmm/ragsec-prompt-injection)

</div>

<br/>

<div align="center">

### 🛠 Stack

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,mysql,docker,aws,git,linux&theme=dark" />
<br/>
<img src="https://skillicons.dev/icons?i=java,spring,ts,react,nextjs,nodejs,cs,vscode&theme=dark" />

</div>

<table>
<tr><td><b>Backend</b></td><td>Python · FastAPI · SQLAlchemy · APIs REST · JWT · Java · Spring Boot · Node.js · .NET</td></tr>
<tr><td><b>Dados</b></td><td>PostgreSQL · MySQL · SQL Server · SQLite · ChromaDB · pgvector</td></tr>
<tr><td><b>IA e LLM</b></td><td>RAG · Segurança de LLM · Llama 3 / Ollama · LangChain · embeddings · Whisper · NLLB</td></tr>
<tr><td><b>Front e infra</b></td><td>React · TypeScript · Next.js · Docker · AWS · Git</td></tr>
</table>

<br/>

<div align="center">

### 💼 Experiência · ~5 anos

</div>

| Período | Onde | O quê |
|:--|:--|:--|
| **set/2026 — atual** | Universidade La Salle | Pesquisador de Iniciação Científica — projeto de resiliência climática e saúde, pelo RS Talentos |
| **mai — nov/2026** | INCBAC | Cientista de Pesquisa e Desenvolvimento — o experimento acima |
| **2026** | Carmillion | Customização de assistentes de IA por caso de uso de cliente |
| **2025 — 2026** | Residência em TIC, BRISA | Backend de sistema para prestadores de serviço: FastAPI, SQLAlchemy, PostgreSQL, JWT, em equipe de seis |
| **2022 — 2024** | Magic Games | Site da empresa — TypeScript no front, Java com Spring Boot no back |

**Formação:** Ciência da Computação na Unilasalle *(conclusão jan/2029)* · Tecnólogo em ADS na UniFatecie *(2028)*

<br/>

<div align="center">

### 🚀 Projetos

</div>

<table>
<tr>
<td width="50%" valign="top">

#### [🤖 Lumi](https://github.com/welerson-py/lumi)

Assistente de mesa distribuído: cliente ESP32 e servidor Python por WebSocket, com LLM local e
reserva offline.

A decisão que importa é de segurança: **o robô nunca envia comando, só o nome de uma ação**,
resolvida contra um registro fechado no servidor. Microfone sempre ligado, na rede local, com
poder de abrir programas — e UID de cartão RFID se clona com celular. Não existe caminho onde
texto da rede vire comando de sistema.

`ESP32` `asyncio` `WebSocket` `Ollama`

</td>
<td width="50%" valign="top">

#### 🇧🇷🤝🇭🇹 Oficina de Imigrantes

Tradução Kreyòl ↔ Português **100% offline**, para inclusão digital de imigrantes haitianos.
Sem internet, sem custo de API.

- **7.000+ frases** extraídas de aulas em vídeo em lote
- Banco vetorial portável: 7.000 frases em **12 MB**, importação em ~5s
- HTTPS local com QR code — o celular entra sem instalar nada
- Cache em disco para TTS e 8 traduções paralelas no NLLB

`faster-whisper` `NLLB-200` `LaBSE` `ChromaDB`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [🔬 RAGSEC](https://github.com/welerson-py/RAGSEC)

O harness de avaliação por trás do artigo. Ingestão, chunking, recuperação por cosseno exato
sobre SQLite, geração em modelos locais e pontuação por múltiplos sinais independentes.

`Python` `SQLite` `Ollama` `pandas`

</td>
<td width="50%" valign="top">

#### 🧠 AURA

RAG local sobre PDF, CSV e TXT corporativos usando modelo local, sem nenhuma dependência de
nuvem.

`LangChain` `ChromaDB` `Streamlit`

</td>
</tr>
</table>

<br/>

<div align="center">

### 📊 GitHub

<img height="165" src="https://github-readme-stats.vercel.app/api?username=welerson-py&show_icons=true&hide_border=true&bg_color=0d1117&title_color=5B9CFF&icon_color=5B9CFF&text_color=c9d1d9&include_all_commits=true&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=welerson-py&layout=compact&hide_border=true&bg_color=0d1117&title_color=5B9CFF&text_color=c9d1d9&langs_count=8"/>

<img width="70%" src="https://streak-stats.demolab.com?user=welerson-py&hide_border=true&background=0d1117&stroke=1f2a3d&ring=5B9CFF&fire=5B9CFF&currStreakLabel=5B9CFF&sideLabels=c9d1d9&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9"/>

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=welerson-py&bg_color=0d1117&color=c9d1d9&line=5B9CFF&point=ffffff&area=true&hide_border=true"/>

<img src="https://github-profile-trophy.vercel.app/?username=welerson-py&theme=onestar&no-frame=true&no-bg=true&column=7&margin-w=8"/>

</div>

<br/>

<div align="center">

### ⚙️ Princípios de engenharia

</div>

```text
Código legível antes de código esperto — manutenção é onde o tempo de verdade é gasto
Contrato explícito — type hints e Pydantic, pra interface não depender de combinação verbal
Log estruturado, não print — depuração em produção exige observabilidade decente
Idempotência em job em lote — rodar duas vezes não pode quebrar nada
Falha óbvia, recuperação graciosa — erro visível é melhor que comportamento estranho
Instrumentar desde o dia um — foi assim que achei quatro bugs meus que me favoreciam
```

<br/>

<div align="center">

<img src="https://raw.githubusercontent.com/welerson-py/welerson-py/output/snake.svg" alt="snake"/>

<br/><br/>

**Português** nativo · **Inglês** avançado — leio documentação técnica diariamente e publiquei artigo científico em inglês

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2f55a4,50:16305c,100:0b1b3a&height=120&section=footer" width="100%"/>

</div>
