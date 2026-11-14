<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xuv044tkq"/><path class="kx62xfbhd"/><path class="okpq0hbid"/><path class="a2_f6pb_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heap-snapshot" /></template>
<style>
.a2_f6pb_f {
  d: path("M15.5 18.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.kx62xfbhd {
  d: path("M2.5 5.5v12q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115t.149.112t.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038q.176.018.355.033q.178.015.359.027q.18.012.363.021q.182.009.365.015t.367.009T10 20l.212-.001m7.288-9.326V5.5");
}

.okpq0hbid {
  d: path("M2.5 11.5q0 .061.009.123q.009.061.027.122t.045.122t.063.121t.081.119t.098.119q.053.058.115.116t.133.115q.07.056.149.112q.079.055.166.109q.086.055.181.107q.095.053.197.104t.212.1t.226.097t.241.093t.254.089t.266.084q.137.042.279.081q.142.038.29.075t.301.071t.311.065q.158.032.321.061q.162.029.328.055q.167.026.337.05q.17.023.343.044t.35.038t.355.033t.359.027q.18.012.363.021q.182.009.365.015t.367.009T10 14l.212-.001M13 14.75h9v7h-9Zm2.25 0L16 13.5h3l.75 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xuv044tkq {
  d: path("M2.5 5.5a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0Z");
}

</style>
