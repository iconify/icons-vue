<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ixc7u3bot"/><path class="j1qzfe2vn"/><path class="ckii3v8im"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-schema" /></template>
<style>
.ckii3v8im {
  d: path("M3 11.25q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115q.066.056.139.112q.074.055.155.109q.081.055.169.107q.088.053.184.104q.095.051.198.1q.102.05.211.097t.224.093q.116.045.237.089q.122.043.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05q.159.023.321.044t.326.038t.331.033t.335.027q.169.012.339.021t.341.015t.343.009q.171.003.343.003q.873 0 1.72-.077m5.153-1.95q.127-.234.127-.473m-2.5 3.25h7v7h-7Zm0 3h7m-3.5 0v4");
}

.ixc7u3bot {
  d: path("M3 5.5a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0Z");
}

.j1qzfe2vn {
  d: path("M3 5.5V17q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115t.139.112t.155.109t.169.107t.184.104q.095.051.198.1q.102.05.211.097t.224.093t.237.089t.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05t.321.044t.326.038t.331.033t.335.027t.339.021t.341.015t.343.009q.171.003.343.003q.873 0 1.72-.077M17 11.742V5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
