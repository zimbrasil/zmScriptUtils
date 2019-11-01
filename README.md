# zmScriptUtils
Scripts utilitários para administração e gerenciamento do Zimbra OSE

**zmDelegateAdmin.sh** | Script para delegar poderes administrativos a um usuário previamente criado. As permissões são:
- criar/editar/deletar novas contas
- criar/editar/deleter listas de distribuição
- criar/editar/deleter recursos
- alterar senhas do usuários
- modificar quota dos usuários

**zm_fix_zpush_lets.sh** | Script para configurar o z-push, letsencrypt e munin do zimbra utilizando o nginx do próprio zimbra. (sem a necessidade de instalar um apache ou nginx externo).

**zm_show_last_logon_date.sh** | Script que lista o último login dos usuários a partir de uma data específica e imprime na tela no formato CSV para que possa ser editado no seu software de planilhas.
