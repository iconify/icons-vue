<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hthkhcbvj"/><path class="dxoki4w_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:internal-developer-portal" /></template>
<style>
.dxoki4w_d {
  d: path("M9 5.75za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9 8.75a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 5.75m6 0za1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M9 11za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 9 14a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 11m6 0za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 14a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 15 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hthkhcbvj {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5V13a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 13V6.5A3.5 3.5 0 0 1 6.5 3m-4 17h19");
}

</style>
