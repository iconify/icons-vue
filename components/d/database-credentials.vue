<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="px0_rhbwh"/><path class="v-d2pgbpt"/><path class="gz4n9mbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-credentials" /></template>
<style>
.gz4n9mbyj {
  d: path("M3 11a7 2.5 0 0 0 14 0m-2.75 8.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4-1.75l3.25-3.25m-1.5 1.5l1.5 1.5");
}

.px0_rhbwh {
  d: path("M3 5a7 2.5 0 1 0 14 0A7 2.5 0 1 0 3 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-d2pgbpt {
  d: path("M3 5v12q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115t.139.112t.155.109t.169.107t.184.104q.095.051.198.1q.102.05.211.097t.224.093t.237.089t.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05t.321.044t.326.038t.331.033t.335.027t.339.021t.341.015t.343.009q.171.003.343.003q.711 0 1.407-.051M17 14.242V5");
}

</style>
