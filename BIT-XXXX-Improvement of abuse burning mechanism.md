# BIT-XXXX: Improvement of abuse burning mechanism

- **BIT Number:** XXXX
- **Title:** Improvement of abuse burning mechanism
- **Status:** Draft
- **Type:** Core
- **Created:** 28/11/2025

---

## Abstract

Based on our statistics, the current miner's emission burning situation as follows:

**42** Subnets: **No burning**.

**3** Subnets: Miner's emission burning ratio between **10% and 30%**.

**5** Subnets: Miner's emission burning ratio between **40% and 50%**.

**6** Subnets: Miner's emission burning ratio between **60% and 70%**.

**9** Subnets: Miner's emission burning ratio between **70% and 80%**.

**1** Subnets: Miner's emission burning ratio between **80% and 90%**.

**4** Subnets: Miner's emission burning ratio between **90% and 95%**.

**5** Subnets: Miner's emission burning ratio between **95% and 99.99%**.

**53** Subnets: Miner's emission burning ratio is **100%**.

---

## Motivation

Many subnets have had their emissions burned for months, yet the **Owner** and **Validator** continue to receive rewards. 

Because the Owner's interests are not affected by the burning of the Miner's emission, the Owner teams are showing very slow progress in project development.

**If the goal is to alleviate sell pressure, the burning should not solely target the Miner's emission.**

---

### ⚠️ The Problem: Abuse of the Burning Mechanism

The current mechanism has led to the abuse of the burning mechanism and created a form of class stratification and interest divergence between the "**Owner**", **Validator**" and the "**Miner**":

* **The Miner's Plight:** Miners operate at the bottom layer of the ecosystem, bearing the costs of computing power, bandwidth, and development. When their emission is burned (or recycled), their income drops to zero, immediately exposing them to the risk of financial loss and forcing them to leave.
* **The Owner's "Guaranteed Income":** Subnet Owners typically take a fixed 18% cut. Even if the subnet's scoring mechanism causes Miners to receive zero score (100% burn), as long as the Root Network continues to allocate weight to that subnet, the Owner still receives their 18%. This gives the Owner **no incentive** to optimize the scoring mechanism or assist the Miners in improving. They may even intentionally maintain a high burn rate to create an appearance of "deflation."
* **Validator's Complacency:** Validators earn a dividend simply by running their validator..

This mechanism makes it easy for the Owner team to become **complacent (or "lie flat")**, lacking the motivation to improve subnet code and enhance the Miner experience.

---

### ✅ Proposed Direction for Improvement

If the purpose is to alleviate sell pressure, then the rewards of the **Validator, Miner, and Owner** should be burned **simultaneously and proportionally**.

### 🌟 Expected Outcomes

* **Mandatory Responsibility Alignment:** To protect their own income, the Owner will be compelled to develop actively, ensuring the scoring mechanism is fair and functional, and that excellent Miners can receive rewards, thereby ensuring they also receive their share.
* **Survival of the Fittest:** "Zombie subnets" with long-term 100% burn rates will become unprofitable for the Owners, eventually forcing them to shut down or be taken over by more competent teams, purifying the ecosystem.
* **True Deflation:** If the goal is to alleviate sell pressure, having the Owner and Validator's rewards burned alongside the Miners will lead to a **more substantial reduction in circulating supply**, and critically, **it will not unilaterally penalize productivity (Miners)**.
