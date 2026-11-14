<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6svg655m"/><path class="ow_gp63pf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-battery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6svg655m {
  d: path("M6.875 4.5h7.75A4.375 4.375 0 0 1 19 8.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-7.75A4.375 4.375 0 0 1 2.5 15.125v-6.25A4.375 4.375 0 0 1 6.875 4.5M21.5 10v4");
}

.ow_gp63pf {
  d: path("M5.5 16.5c0-6.5 4-9 10.5-9c0 6.5-4 9-10.5 9m0 0l6-5");
}

</style>
