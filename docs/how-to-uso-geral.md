# Como Usar o Framework de Otimização de LinkedIn

Este guia descreve o processo **completo e cronológico**.

---

## ETAPA 1 — Preparação

- Leia e preencha corretamente o `PROFESSIONAL_CONTEXT`
- Configure o perfil LinkedIn para visibilidade
- Separe o conteúdo real do seu LinkedIn

---

## ETAPA 2 — PROMPT 1 (ANÁLISE)

Arquivo:
`prompts/prompt_analysis_Profile.xml`

1. Preencha `<PROFESSIONAL_CONTEXT>`
2. Preencha `<INPUT_DATA>` com dados reais
3. Copie todo o XML
4. Execute na IA

Resultado:
- Relatório
- `ANALYSIS_HANDOFF.txt`

---

## ETAPA 3 — PROMPT 2 (OTIMIZAÇÃO)

Arquivo:
`prompts/prompt_optimization_Profile.xml`

1. Mantenha o mesmo `PROFESSIONAL_CONTEXT`
2. Cole o HANDOFF completo no CDATA
3. Execute na IA

Resultados:
- Headline
- About
- Skills
- Boolean
- Ajustes por seção
- Plano 30–90 dias

---

## ETAPA 4 — Aplicação no LinkedIn

Aplicar na ordem:
1. Headline
2. About
3. Skills
4. Experiências
5. Em destaque

---

## Boas Práticas

- Não misture trilhas profissionais
- Sempre use métricas
- Refazer análise em grandes mudanças de carreira