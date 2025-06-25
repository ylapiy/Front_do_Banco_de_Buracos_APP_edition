# Desemburaca Teresina - App🕳🚧

Aplicativo do Desemburaca Teresina, sendo uma aplicação para denúncia de buracos nas vias públicas de Teresina, desenvolvido como projeto acadêmico do Centro Universitário iCEV.

## 📋 Sobre o Projeto

O _Desemburaca Teresina_ é uma plataforma que facilita a comunicação entre cidadãos e a prefeitura municipal para reportar problemas de infraestrutura viária. O sistema permite que os usuários fotografem buracos nas ruas e enviem denúncias com localização GPS automática, agilizando o processo de manutenção urbana.

## ✨ Funcionalidades

- 📸 _Captura de fotos_ com dados GPS automáticos
- 📍 _Geolocalização precisa_ dos problemas reportados
- 🗺 _Validação geográfica_ para área de Teresina
- 💾 _Armazenamento offline_ para envio posterior

### 🛠 Tecnologias Utilizadas

## Trasnformção em Aplicativo

- _Capactors_ - Usado para fazer o aplicativo nativo (para possivel publicação na playstore)
- _Android Studio_ - Usando para debugar e gerar o APK

### Frontend

- _HTML5_ - Estrutura das páginas
- _CSS3_ - Estilização e responsividade
- _JavaScript_ - Lógica da aplicação
- _EXIF.js_ - Extração de metadados de imagens
- _Turf.js_ - Operações geoespaciais

### Backend/APIs

- _Repositorio com o back_ - https://github.com/ditimon01/Projeto_Desemburaca_Teresina_API
- _Repositorio com a pagina do Banco de Dados_ - https://github.com/ylapiy/PaginaBancodeDados-DesemburacaTeresina.git
- _LocationIQ API_ - Geocodificação reversa
- _Railway_ - Hospedagem da API
- _Google Drive API_ - Armazenamento de imagens
- _PostgreSQL - Neon_ - Banco de dados
- _FormSubmit_ - Email de suporte

## 📁 Estrutura do Projeto

desemburaca-teresina/
├── app/
│ ├── home/ # Página inicial
│ ├── form/ # Formulário de denúncia
│ ├── serv/ # Visualização de serviços
│ ├── sobre/ # Informações do projeto
│ └── ajuda/ # Página de ajuda
├── assets/ # Recursos estáticos
│ ├── images/ # Imagens do projeto
│ └── icons/ # Ícones da interface
├── index.html # Redirecionamento inicial
├── loading.css # Css para tela de carregaemnto
├── Documentação.pdf # Documentação das princiapis partes do codigo (100% de certeza esta desatualizada a essa ponto)
└── README.md

## 📱 Como Usar

### Para Cidadãos

1. _Acesse a página inicial_ e clique em "Submeter"
2. _Preencha o formulário_ com:
   - Localização do buraco
   - Tamanho aproximado
   - Descrição detalhada
3. _Tire uma foto_ usando a câmera ou faça upload
4. _Envie a denúncia_ - o sistema validará automaticamente a localização GPS

### Validações Automáticas

- ✅ _GPS ativo_: Foto deve conter coordenadas
- ✅ _Área válida_: Localização dentro de Teresina
- ✅ _Data válida_: Imagem deve ter timestamp
- ✅ _Conectividade_: Modo offline disponível

## 🔧 Configuração da API

O projeto utiliza APIs externas que requerem configuração:

### LocationIQ (Geocodificação)

### Backend Railway

### FormSubmit (Email)

## 📊 Funcionalidades Técnicas

### Processamento de Imagens

- Extração automática de dados EXIF
- Validação de coordenadas GPS
- Conversão de formatos de coordenadas
- Verificação de limites geográficos

### Modo Offline

- Armazenamento local com IndexedDB
- Sincronização automática quando online
- Interface adaptativa para status de conexão

## 👥 Equipe de Desenvolvimento

| Nome | Função |
| ------------------------------- | ------------------ | |
| _Augusto César A. M. Neto_ | Frontend / Backend |
| _Ygor Jivago Leal Félix_ | Frontend / Backend |
| _Vinicius Azevedo da Fonseca_ | Backend |
| _Mateus Farias_ | Backend |

## 🎓 Instituição

_Centro Universitário iCEV_  
Projeto acadêmico desenvolvido como parte do curso de graduação.

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos. Todos os direitos reservados à Prefeitura Municipal de Teresina - Desemburaca Teresina © 2025.

## 🔄 Status do Projeto

🚧 _Em desenvolvimento ativo_ - Projeto acadêmico em fase de finalização

---

*Ajude a melhorar Teresina! Denuncie buracos e contribua para uma cidade melhor.* 🏙✨
