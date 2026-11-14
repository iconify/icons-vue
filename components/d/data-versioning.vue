<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yhkosbc6e"/><path class="oesjjk6fx"/><path class="tp6s-_6vg"/><path class="wh9f-4brs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-versioning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oesjjk6fx {
  d: path("M3 5.5v12q0 .061.01.123q.009.061.029.122q.019.061.048.122q.028.061.067.121q.038.06.086.119q.047.06.104.119t.124.116q.066.058.141.115q.075.056.159.112q.084.055.177.109q.092.055.193.107q.101.053.21.104t.226.1t.242.097t.256.093t.271.089t.285.084q.145.042.297.081q.152.038.309.075q.158.037.321.071q.164.034.332.065q.169.032.342.061t.351.055t.359.05t.366.044t.373.038t.378.033t.383.027t.387.021t.39.015t.391.009Q10.804 20 11 20q.852 0 1.684-.056M19 11.81V5.5");
}

.tp6s-_6vg {
  d: path("M3 10.5q0 .061.01.123q.009.061.029.122q.019.061.048.122q.028.061.067.121q.038.06.086.119q.047.06.104.119t.124.116q.066.058.141.115q.075.056.159.112q.084.055.177.109q.092.055.193.107q.101.053.21.104t.226.1t.242.097t.256.093t.271.089t.285.084q.145.042.297.081q.152.038.309.075q.158.037.321.071q.164.034.332.065q.169.032.342.061t.351.055t.359.05q.181.023.366.044t.373.038t.378.033t.383.027q.193.012.387.021t.39.015t.391.009Q10.804 13 11 13q1.126 0 2.208-.097m3.839-.766q.234-.085.443-.175q.208-.091.391-.187q.182-.096.336-.196q.154-.101.279-.206t.219-.212t.158-.217q.063-.11.095-.221T19 10.5m-3.5 4V22m3-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.wh9f-4brs {
  d: path("M20 17.5v.5a2.5 2.5 0 0 1-2.5 2.5h-2");
}

.yhkosbc6e {
  d: path("M3 5.5a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0");
}

</style>
