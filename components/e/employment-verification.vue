<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jdx9uiwos"/><path class="dz1zt4bxs"/><path class="ivektacxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:employment-verification" /></template>
<style>
.dz1zt4bxs {
  d: path("M9.75 16.25a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m7.25 3l2.5 2.5M5 7.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M10.5 6h3m-3 3h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ivektacxu {
  d: path("m12 16.25l1.5 1.5L16 15");
}

.jdx9uiwos {
  d: path("M6 2.5h7A3.5 3.5 0 0 1 16.5 6v2.5A3.5 3.5 0 0 1 13 12H6a3.5 3.5 0 0 1-3.5-3.5V6A3.5 3.5 0 0 1 6 2.5");
}

</style>
