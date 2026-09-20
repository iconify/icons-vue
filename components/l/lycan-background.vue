<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="dbnj_vbgs"/><path class="f8n9xgb8y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lycan-background" /></template>
<style>
.dbnj_vbgs {
  fill: var(--svg-color--ff7d34, #ff7d34);
  d: path("M24 0H0v24h24z");
}

.f8n9xgb8y {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.05 4.515l-.003-.047l-.035.022l-.038.026l-.972.707q-1.769 1.289-3.542 2.57a.26.26 0 0 0-.12.238q.002 5.652.002 11.306v.094c.003.1.016.107.113.076q.704-.23 1.408-.457a.15.15 0 0 0 .108-.108l.256-.895v-.001l.159-.55a606 606 0 0 1 .71-2.477l.227-.789l.198-.7l.19-.665q.091-.32.185-.64v-.002l.161-.555l.185-.65l.144-.504l.287-.996l.091-.313q.097-.33.19-.66a1.7 1.7 0 0 0 .094-.424q.007-1.346.004-2.693v-.849zm-5.388 9.2q-.003-2.847.002-5.693a.23.23 0 0 0-.11-.21L9.9 6.61L7.042 4.532a.3.3 0 0 0-.082-.03a.4.4 0 0 0-.015.08v3.55a.4.4 0 0 0 .011.1l.474 1.65l.186.642l.229.79l.145.51l.14.495l.195.675l.195.674l.135.476l.146.515l.21.728l.001.001l.181.627l.14.488l.113.398l.158.548l.147.508q.145.503.286 1.005a.12.12 0 0 0 .093.092l.558.18l.227.075l.637.207c.096.031.11.021.11-.078zm3.411 3.796l2.464-8.628l.04-.023a.3.3 0 0 0 .032.07l2.356 2.965a.14.14 0 0 1 .026.142q-.088.293-.17.59l-.076.272l-.124.436v.002l-.133.46l-.004.015q-.077.27-.15.542a.33.33 0 0 1-.132.2a202 202 0 0 0-1.578 1.145l-1.925 1.4l-.53.384q-.022.016-.046.03l-.023.013zm-6.193.009l.03.018c.002-.104-2.416-8.598-2.477-8.648l-.078.093l-.418.526q-.95 1.2-1.903 2.396a.13.13 0 0 0-.027.128q.135.46.265.922l.147.522q.131.468.265.934a.24.24 0 0 0 .08.117l1.6 1.167l2.46 1.789z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
