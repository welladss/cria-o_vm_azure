# criacao_vm_azure
Criação de Máquina Virtual (Desafio DIO)

---

Este repositório contém anotações e resumos sobre o processo de criação e configuração de uma máquina virtual na plataforma Microsoft Azure. O projeto faz parte do desafio proposto pela DIO.

---

Objetivos de Aprendizagem

- Praticar a criação de uma VM no Azure
- Documentar os passos técnicos de forma clara

----

Etapas Realizadas

1.  **Acesso ao Portal do Azure**
   - https://portal.azure.com

2.  **Criação da Máquina Virtual**
   - Sistema Operacional: Windows Server 2022
   - Região: Brazil South
   - Tamanho da VM: B1s (grátis elegível)
   - Usuário criado: "dioazure"
   - Acesso remoto: RDP (porta 3389 aberta)

3. **Configurações adicionais**
   - Disco padrão SSD
   - IP público dinâmico
   - Grupo de segurança configurado com acesso liberado apenas à porta RDP

4. **Conexão via Remote Desktop**
   - Testado com sucesso a partir do aplicativo Conexão de Área de Trabalho Remota



Dicas

- Desligue a VM quando não estiver usando para não gastar créditos do Azure
- Use nomes intuitivos para recursos
- Aproveite a camada gratuita do Azure, mas acompanhe os custos pelo painel
