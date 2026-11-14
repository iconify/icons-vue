<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="llkdb3bzx"/><path class="fv3j09boa"/><path class="qdkzmyb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-trigger" /></template>
<style>
.fv3j09boa {
  d: path("M2.5 4.5V14q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115q.07.056.149.112q.079.055.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q.861 0 1.7-.065q.838-.065 1.611-.192m4.189-4.47V4.5");
}

.llkdb3bzx {
  d: path("M2.5 4.5a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0Z");
}

.qdkzmyb-c {
  d: path("M2.5 9.25a7.5 2.5 0 0 0 15 0m2 4.5l-4.25 4.5l5.5-.5L16.5 22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
