<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u3ff-6_ms"/><path class="y7_z2--eq"/><path class="cyk5aqb2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bits-cheer" /></template>
<style>
.cyk5aqb2z {
  d: path("M3 9a7 2.5 0 0 0 14 0M3 13q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115q.066.056.139.112q.074.055.155.109q.081.055.169.107q.088.053.184.104q.095.051.198.1q.102.05.211.097t.224.093q.116.045.237.089q.122.043.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05q.159.023.321.044t.326.038t.331.033t.335.027q.169.012.339.021t.341.015t.343.009q.171.003.343.003q.928 0 1.824-.086M16 15h4a1.5 1.5 0 0 1 1.5 1.5V18a1.5 1.5 0 0 1-1.5 1.5h-1.474a1.5 1.5 0 0 0-.937.329l-1.308 1.046a.481.481 0 0 1-.781-.375V20a.5.5 0 0 0-.5-.5a.5.5 0 0 1-.5-.5v-2.5A1.5 1.5 0 0 1 16 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u3ff-6_ms {
  d: path("M3 5a7 2.5 0 1 0 14 0A7 2.5 0 1 0 3 5");
}

.y7_z2--eq {
  d: path("M3 5v12q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115t.139.112t.155.109t.169.107t.184.104q.095.051.198.1q.102.05.211.097t.224.093t.237.089t.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05t.321.044t.326.038t.331.033t.335.027t.339.021t.341.015t.343.009q.171.003.343.003q.873 0 1.72-.077M17 12.242V5");
}

</style>
