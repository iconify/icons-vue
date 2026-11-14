<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hbs9iqbjl"/><path class="ndq-tib0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leak-sensor-dry" /></template>
<style>
.hbs9iqbjl {
  d: path("M2.5 9.5a8 3 0 1 0 16 0a8 3 0 1 0-16 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ndq-tib0i {
  d: path("M2.5 9.5V13q0 .074.01.147q.009.074.029.147q.019.073.048.146q.028.073.067.145q.038.073.086.144t.104.142t.124.14q.066.069.141.137t.159.135t.177.131q.092.065.193.128t.21.125t.226.12t.242.116t.256.112t.271.106t.285.102q.145.049.297.096t.309.091q.158.043.321.084q.164.041.332.079q.169.038.342.073t.351.066t.359.06t.366.053t.373.046t.378.039q.191.018.383.032q.193.015.387.026t.39.018t.391.01q.197.004.393.004q1.255 0 2.45-.144m2.571-.52q.348-.106.662-.224t.591-.251q.277-.131.514-.273q.236-.142.429-.293q.193-.152.339-.31t.246-.321q.099-.164.148-.33q.05-.167.05-.334V9.5M2.5 16H12m2.75 2l2 2L21 15.75");
}

</style>
