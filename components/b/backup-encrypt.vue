<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h6h7z1bhr"/><path class="ilik_cbwn"/><path class="g5ivemsfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backup-encrypt" /></template>
<style>
.g5ivemsfr {
  d: path("M3.5 11.75q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115q.07.056.149.112q.079.055.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038t.355.033t.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q.918 0 1.81-.074q.891-.074 1.702-.217m3.841-1.716q.147-.244.147-.493M15 17.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.h6h7z1bhr {
  d: path("M3.5 5.5a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0Z");
}

.ilik_cbwn {
  d: path("M3.5 5.5V18q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115t.149.112t.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009t.368.003q.622 0 1.235-.034m6.265-8.193V5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
