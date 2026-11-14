<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekf2s55jf"/><path class="xdbrurb4d"/><path class="hjwtwgb_c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:job-application" /></template>
<style>
.ekf2s55jf {
  d: path("M2.5 15H6l4 2.5h4.25a1.25 1.25 0 0 1 0 2.5H9.5");
}

.hjwtwgb_c {
  d: path("M12.25 5.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-1 4c0-1 1-1.5 2.25-1.5s2.25.5 2.25 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdbrurb4d {
  d: path("M2.5 21.5H13l7.25-4.75c1-.75.25-2.25-1-1.75l-3.75 2.5m-4.062-15h4.125a2.19 2.19 0 0 1 2.187 2.188v5.375a2.19 2.19 0 0 1-2.187 2.187h-4.125a2.19 2.19 0 0 1-2.188-2.187V4.688A2.19 2.19 0 0 1 11.438 2.5");
}

</style>
