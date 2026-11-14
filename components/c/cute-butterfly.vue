<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lne2jegec"/><path class="uj-ufe_gr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cute-butterfly" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lne2jegec {
  d: path("M10.25 12a1.75 6.5 0 1 0 3.5 0a1.75 6.5 0 1 0-3.5 0");
}

.uj-ufe_gr {
  d: path("M10.75 7.5C6 2 1 3.5 3 8.5c1 2 4 3.25 7.25 3.25C6.5 12.25 4 14 4.5 17s4 3 6-1m2.75-8.5C18 2 23 3.5 21 8.5c-1 2-4 3.25-7.25 3.25C17.5 12.25 20 14 19.5 17s-4 3-6-1");
}

</style>
