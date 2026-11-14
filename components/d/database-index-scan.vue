<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jhoq949qr"/><path class="l-thecbol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-index-scan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhoq949qr {
  d: path("M3 5.5a8 3 0 1 0 16 0a8 3 0 1 0-16 0");
}

.l-thecbol {
  d: path("M3 5.5V18q0 .074.01.147q.009.074.029.147q.019.073.048.146q.028.073.067.145q.038.073.086.144t.104.142q.057.07.124.14q.066.069.141.137t.159.135q.084.066.177.131t.193.128q.101.063.21.125q.109.061.226.12t.242.116t.256.112q.132.054.271.106t.285.102q.145.049.297.096t.309.091q.158.043.321.084q.164.041.332.079q.169.038.342.073t.351.066t.359.06q.181.028.366.053t.373.046t.378.039t.383.032q.193.015.387.026t.39.018t.391.01Q10.804 21 11 21q1.368 0 2.658-.17M19 12.63V5.5m-12.5 6H11m-4.5 4h3m5.75 2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
