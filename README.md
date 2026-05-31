[Untitled.md](https://github.com/user-attachments/files/28434060/Untitled.md)
```json!
{
  "season_id": "y8s1",
  "lang": "pt",
  "ui": {
    "loading": "Carregando dados de MODs da temporada...",
    "failed": "Falha ao carregar dados de MODs da temporada.",
    "noData": "Sem dados",
    "sectionSimulator": "Simulador",
    "sectionActive": "Lista de MODs ativos",
    "sectionPassive": "Lista de MODs passivos",
    "season": "Temporada",
    "globalModifier": "MOD global",
    "activeModifier": "MOD ativo",
    "activeLevel": "Nível ativo",
    "picker": "Seleção de candidatos",
    "share": "Compartilhar",
    "pickerAddTrait": "Característica especificada",
    "pickerAdd": "Adicionar",
    "pickerConds": "Condições",
    "pickerNoCond": "Sem condições",
    "pickerCandidates": "Número de candidatos",
    "pickerClose": "Fechar",
    "passiveSlot1": "MOD passivo",
    "passiveSlot2": "MOD passivo",
    "passiveSlot3": "MOD passivo",
    "none": "Nenhum",
    "result": "Resultado",
    "module": "Módulo",
    "base": "Base",
    "final": "Final",
    "delta": "Diferença",
    "offense": "Ataque",
    "defense": "Defesa",
    "utility": "Utilitário",
    "wildcard": "Curinga",
    "dropped": "Excluído pelo limite de equipamento",
    "duplicated": "Excluído por duplicidade",
    "cooldown": "Recarga",
    "desc": "Descrição",
    "group": "Grupo",
    "name": "Nome",
    "icon": "Ícone",
    "orderApplied": "Ordem de aplicação",
    "activeDerived": "Efeito ativo (valor atual)",
    "formula": "Fórmula",
    "moduleStacks": "Acúmulos de módulo",
    "stackValue": "Valor acumulado",
    "buffEffect": "Efeito",
    "levelEffects": "Efeitos de nível",
    "perStack": "Por acúmulo",
    "noStatBuff": "Sem bônus de atributo",
    "selectedMods": "MODs selecionados",
    "passiveMods": "MODs passivos",
    "slot": "Slot",
    "mod": "MOD",
    "effect": "Efeito",
    "empRadius": "Raio do EMP",
    "repairPerSec": "Reparos/s",
    "skillCdr": "Redução da recarga de habilidades",
    "pulseDuration": "Duração do pulso",
    "blindDuration": "Duração da cegueira",
    "overchargeDuration": "Duração da Sobrecarga",
    "copyUrlSuccess": "URL copiada.",
    "copyUrlFailed": "Falha ao copiar URL.",
    "unitSecond": "s",
    "levelIncreaseBaseStacks": "Acúmulos base de todos os módulos +",
    "cooldownReductionPrefix": "Redução de recarga:",
    "perStackByModule": "por acúmulo de",
    "stackSuffix": ""
  },
  "global_modifier": {
    "name": "TODO:Recombinant"
  },
  "active_modifiers": [
    {
      "id": "blackout_pulse",
      "name": "TODO:Blackout Pulse",
      "desc": "TODO:Ative para liberar um pulso eletromagnético que destrói dispositivos inimigos e eletrocuta todos os inimigos em um raio de 10m (base, mais 0,5m por acúmulo ofensivo).",
      "desc_template": "TODO:Ative para liberar um pulso eletromagnético que destrói dispositivos inimigos e eletrocuta todos os inimigos dentro de um raio de {{emp_radius}} (10m base, mais 0,5m por acúmulo ofensivo)."
    },
    {
      "id": "cloud_armor",
      "name": "TODO:Cloud Armor",
      "desc": "TODO:Ative para reparar a armadura de você e de seus aliados em um raio de 10 metros, a uma taxa de Armadura total por segundo (5% base, mais 0,2% por acúmulo de Defensivo). Este efeito dura um total de 10 segundos.",
      "desc_template": "TODO:Ative para reparar a armadura de você e de seus aliados em um raio de 10m, a uma taxa de {{repair_per_sec}} de armadura total por segundo (5% base, mais 0,2% por acúmulo de Defesa). Este efeito dura um total de 10 segundos."
    },
    {
      "id": "optimize_overload",
      "name": "TODO:Otimizar/Sobrecarregar",
      "desc": "TODO:Ative para reduzir o tempo de recarga das suas habilidades ativas (30% base, mais 0,8% por acúmulo de Utilidade).",
      "desc_template": "TODO:Ative para reduzir o tempo de recarga das suas habilidades ativas em {{skill_cdr}} (30% base, mais 0,8% por acúmulo de Utilidade)."
    }
  ],
  "passive_modifiers": [
    {
      "id": "offense_amplify",
      "name": "TODO:Amplificar",
      "desc": "TODO:Aumenta os acúmulos de Ataque em 5."
    },
    {
      "id": "offense_consume",
      "name": "TODO:Consume",
      "desc": "TODO:Aumenta os acúmulos de Ataque em 10, diminui os acúmulos de Defesa e Utilidade em 5 cada."
    },
    {
      "id": "offense_saturate",
      "name": "TODO:Saturate",
      "desc": "TODO:Increase Offense stacks by 25, but Offense stacks no longer affect Weapon Handling, Headshot Damage, or Magazine Size."
    },
    {
      "id": "offense_pivot",
      "name": "TODO:Pivot",
      "desc": "TODO:Increase the lowest module stacks by 15, decrease Offense stacks by 10. If Offense is lowest, or Defense and Utility tie for lowest, nothing happens."
    },
    {
      "id": "offense_split",
      "name": "TODO:Split",
      "desc": "TODO:Decrease Offense stacks by 15, increase Defense and Utility stacks by 10 each."
    },
    {
      "id": "offense_compress",
      "name": "TODO:Compress",
      "desc": "TODO:Decrease Offense stacks by 10, but each Offense stack is 50% more potent when calculating affected stats."
    },
    {
      "id": "offense_convert_1",
      "name": "TODO:Convert 1",
      "desc": "TODO:Offense stacks no longer affect Weapon Handling; instead they increase Headshot Damage at 3% per Offense stack."
    },
    {
      "id": "offense_convert_2",
      "name": "TODO:Convert 2",
      "desc": "TODO:Offense stacks no longer affect Weapon Handling; instead they increase Magazine Size at 1% per Offense stack."
    },
    {
      "id": "offense_stabilize",
      "name": "TODO:Stabilize",
      "desc": "TODO:Offense stacks are locked and cannot change. Their base value may still increase by leveling up Blackout Pulse."
    },
    {
      "id": "offense_invert",
      "name": "TODO:Invert",
      "desc": "TODO:Swap Offense stacks with the current highest module stacks. If Offense is already highest, or Defense and Utility tie for highest, nothing happens."
    },
    {
      "id": "defense_amplify",
      "name": "TODO:Amplify",
      "desc": "TODO:Increase Defense stacks by 5."
    },
    {
      "id": "defense_consume",
      "name": "TODO:Consume",
      "desc": "TODO:Increase Defense stacks by 10, decrease Offense and Utility stacks by 5 each."
    },
    {
      "id": "defense_saturate",
      "name": "TODO:Saturate",
      "desc": "TODO:Increase Defense stacks by 25, but Defense stacks no longer affect Armor, Protection from Elites, or Hazard Protection."
    },
    {
      "id": "defense_pivot",
      "name": "TODO:Pivot",
      "desc": "TODO:Increase the lowest module stacks by 15, decrease Defense stacks by 10. If Defense is lowest, or Offense and Utility tie for lowest, nothing happens."
    },
    {
      "id": "defense_split",
      "name": "TODO:Split",
      "desc": "TODO:Decrease Defense stacks by 15, increase Offense and Utility stacks by 10 each."
    },
    {
      "id": "defense_compress",
      "name": "TODO:Compress",
      "desc": "TODO:Decrease Defense stacks by 10, but each Defense stack is 50% more potent when calculating affected stats."
    },
    {
      "id": "defense_convert_1",
      "name": "TODO:Convert 1",
      "desc": "TODO:Defense stacks no longer affect Armor; instead they increase Protection from Elites at 0.5% per Defense stack."
    },
    {
      "id": "defense_convert_2",
      "name": "TODO:Convert 2",
      "desc": "TODO:Defense stacks no longer affect Armor; instead they increase Hazard Protection at 1% per Defense stack."
    },
    {
      "id": "defense_stabilize",
      "name": "TODO:Stabilize",
      "desc": "TODO:Defense stacks are locked and cannot change. Their base value may still increase by leveling up Cloud Armor."
    },
    {
      "id": "defense_invert",
      "name": "TODO:Invert",
      "desc": "TODO:Swap Defense stacks with the current highest module stacks. If Defense is already highest, or Offense and Utility tie for highest, nothing happens."
    },
    {
      "id": "utility_amplify",
      "name": "TODO:Amplify",
      "desc": "TODO:Increase Utility stacks by 5."
    },
    {
      "id": "utility_consume",
      "name": "TODO:Consume",
      "desc": "TODO:Increase Utility stacks by 10, decrease Offense and Defense stacks by 5 each."
    },
    {
      "id": "utility_saturate",
      "name": "TODO:Saturate",
      "desc": "TODO:Increase Utility stacks by 25, but Utility stacks no longer affect Skill Damage, Skill Repair, or Status Effects."
    },
    {
      "id": "utility_pivot",
      "name": "TODO:Pivot",
      "desc": "TODO:Increase the lowest module stacks by 15, decrease Utility stacks by 10. If Utility is lowest, or Offense and Defense tie for lowest, nothing happens."
    },
    {
      "id": "utility_split",
      "name": "TODO:Split",
      "desc": "TODO:Decrease Utility stacks by 15, increase Offense and Defense stacks by 10 each."
    },
    {
      "id": "utility_compress",
      "name": "TODO:Compress",
      "desc": "TODO:Decrease Utility stacks by 10, but each Utility stack is 50% more potent when calculating affected stats."
    },
    {
      "id": "utility_convert_1",
      "name": "TODO:Convert 1",
      "desc": "TODO:Utility stacks no longer affect Skill Damage; instead they increase Skill Repair at 1% per Utility stack."
    },
    {
      "id": "utility_convert_2",
      "name": "TODO:Convert 2",
      "desc": "TODO:Utility stacks no longer affect Skill Damage; instead they increase Status Effects at 1% per Utility stack."
    },
    {
      "id": "utility_stabilize",
      "name": "TODO:Stabilize",
      "desc": "TODO:Utility stacks are locked and cannot change. Their base value may still increase by leveling up Optimize/Overload."
    },
    {
      "id": "utility_invert",
      "name": "TODO:Invert",
      "desc": "TODO:Swap Utility stacks with the current highest module stacks. If Utility is already highest, or Offense and Defense tie for highest, nothing happens."
    },
    {
      "id": "wildcard_cascade",
      "name": "TODO:Cascade",
      "desc": "TODO:Stats and Active Modifiers are no longer affected by the highest module stacks, but half of that value is added to each of the other two modules. If two or more modules tie for highest, nothing happens."
    },
    {
      "id": "wildcard_converge",
      "name": "TODO:Converge",
      "desc": "TODO:Increase the lowest module stacks by the average of the other two stacks, but set those two stacks to 0. If two or more modules tie for lowest, nothing happens."
    },
    {
      "id": "wildcard_equalize",
      "name": "TODO:Equalize",
      "desc": "TODO:All module stacks become equal to the middle-value stack. If the middle-value stack equals either highest or lowest, nothing happens."
    },
    {
      "id": "wildcard_nullify",
      "name": "TODO:Nullify",
      "desc": "TODO:Inverte as alterações de valor aplicadas às pilhas de módulos mais baixas (adições tornam-se subtrações e vice-versa). Os modificadores de inversão não são afetados."
    }
  ]
}

```
