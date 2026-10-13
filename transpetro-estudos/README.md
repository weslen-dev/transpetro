# Transpetro Estudos 2026

Painel web estático para acompanhar a preparação para o concurso Transpetro: dashboard, calendário, matérias, registro de estudos, questões, caderno de erros, revisões espaçadas, relatórios e exportação dos dados.

## Executar localmente

Basta abrir `index.html` em um navegador moderno. Não precisa instalar dependências nem configurar banco de dados.

## Publicar na Vercel

1. Crie um repositório Git e envie os arquivos desta pasta.
2. Na Vercel, escolha **Add New → Project** e importe o repositório.
3. Como é um site estático, deixe o framework como **Other** e não configure build command. A raiz do projeto deve conter `index.html`.
4. Clique em **Deploy**.

Também é possível fazer deploy pela CLI da Vercel na pasta do projeto, usando `vercel` e depois `vercel --prod`.

## Dados e privacidade

Os registros são salvos no `localStorage` do navegador/dispositivo. Isso significa que não há sincronização automática entre computadores ou navegadores. Use **Exportar dados** para salvar um backup JSON regularmente. Limpar os dados do navegador pode apagar os registros locais.

## Recursos

- Dashboard com horas, questões, acertos e revisões pendentes.
- Calendário mensal com sessões planejadas e marcação de conclusão.
- Cadastro e acompanhamento de matérias e metas.
- Registro de blocos de questões e cálculo automático de aproveitamento.
- Caderno de erros, com status pendente/resolvido.
- Revisões agendadas e conclusão de revisão.
- Relatórios e exportação CSV/JSON.
- Layout responsivo para computador e celular.

A lista de matérias é uma sugestão de organização e deve ser conferida com o edital oficial e suas retificações.
