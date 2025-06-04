
# SWOT Consultoria - Site Estático

Este é o site estático da SWOT Consultoria, criado com HTML, CSS e JavaScript puros para funcionar diretamente em servidores web tradicionais como a Hostinger.

## Estrutura do Projeto

```
static/
├── index.html          # Página inicial
├── quem-somos.html     # Página sobre a empresa
├── servicos.html       # Página de serviços
├── blog.html           # Página do blog
├── contato.html        # Página de contato
├── styles.css          # Estilos CSS
├── script.js           # JavaScript
└── README.md           # Este arquivo
```

## Como Fazer Upload na Hostinger

1. **Acesse o File Manager** da sua conta Hostinger
2. **Navegue até a pasta `public_html`**
3. **Delete qualquer conteúdo anterior** (se houver)
4. **Faça upload de todos os arquivos** desta pasta `static`
5. **Certifique-se** que o arquivo `index.html` está na raiz da `public_html`

## Recursos do Site

- **Design Responsivo**: Funciona em desktop, tablet e mobile
- **Navegação Intuitiva**: Menu de navegação em todas as páginas
- **Formulário de Contato**: Formulário funcional na página de contato
- **Botão WhatsApp**: Botão flutuante para contato direto
- **Animações CSS**: Efeitos visuais suaves
- **SEO Otimizado**: Meta tags e estrutura semântica

## Páginas Incluídas

1. **Início** (`index.html`): Página principal com hero, serviços e estatísticas
2. **Quem Somos** (`quem-somos.html`): História, missão, visão e valores
3. **Serviços** (`servicos.html`): Detalhes dos serviços oferecidos
4. **Blog** (`blog.html`): Artigos e insights
5. **Contato** (`contato.html`): Formulário e informações de contato

## Personalização

### Alterar Número do WhatsApp
No arquivo `script.js`, linha 47:
```javascript
const phoneNumber = "5566999999999"; // Substitua pelo número real
```

### Alterar E-mail de Contato
Nos arquivos HTML, procure por:
```html
contato@swotconsultoria.com.br
```
E substitua pelo e-mail real.

### Alterar Imagens
As imagens atualmente usam URLs do Unsplash. Para usar imagens próprias:
1. Faça upload das imagens para a pasta `public_html`
2. Substitua as URLs nos arquivos HTML

## Suporte a Navegadores

- Chrome (todas as versões recentes)
- Firefox (todas as versões recentes)
- Safari (todas as versões recentes)
- Edge (todas as versões recentes)
- Internet Explorer 11+

## Licença

Este projeto foi criado para a SWOT Consultoria. Todos os direitos reservados.
