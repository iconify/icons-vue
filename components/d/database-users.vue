<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nmvawm33q"/><path class="y6s6g18kx"/><path class="e0gy3ibyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-users" /></template>
<style>
.e0gy3ibyu {
  d: path("M2.5 11q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115q.066.056.139.112q.074.055.155.109q.081.055.169.107q.088.053.184.104q.095.051.198.1q.102.05.211.097t.224.093q.116.045.237.089q.122.043.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05q.159.023.321.044t.326.038t.331.033t.335.027q.169.012.339.021t.341.015t.343.009q.171.003.343.003q.912 0 1.793-.083q.881-.084 1.673-.245m2.784.328a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2.5 8.25c0-2.25 2-3.5 4.5-3.5s4 1.25 4 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nmvawm33q {
  d: path("M2.5 5a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0");
}

.y6s6g18kx {
  d: path("M2.5 5v12q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115t.139.112t.155.109t.169.107t.184.104q.095.051.198.1q.102.05.211.097t.224.093t.237.089t.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05t.321.044t.326.038t.331.033t.335.027q.169.012.339.021t.341.015t.343.009q.171.003.343.003q.711 0 1.407-.051M16.5 8.842V5");
}

</style>
