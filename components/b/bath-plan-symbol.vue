<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gs49b8b5j"/><path class="t_22xsbjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bath-plan-symbol" /></template>
<style>
.gs49b8b5j {
  d: path("M6.875 5.5h10.25A4.375 4.375 0 0 1 21.5 9.875v4.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 14.125v-4.25A4.375 4.375 0 0 1 6.875 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t_22xsbjg {
  d: path("M9 8.25h6A3.75 3.75 0 0 1 18.75 12A3.75 3.75 0 0 1 15 15.75H9A3.75 3.75 0 0 1 5.25 12A3.75 3.75 0 0 1 9 8.25M15.5 12h.01");
}

</style>
