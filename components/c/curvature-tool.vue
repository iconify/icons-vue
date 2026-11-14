<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_-p8-6pj"/><path class="zmiqfrnyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:curvature-tool" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_-p8-6pj {
  d: path("m8.72 18.906l-3.867-6.329a1.5 1.5 0 0 1-.154-1.223l1.475-4.795A1.5 1.5 0 0 1 7.608 5.5h4.784a1.5 1.5 0 0 1 1.434 1.059l1.475 4.795a1.5 1.5 0 0 1-.154 1.223l-3.867 6.329a1.5 1.5 0 0 1-2.56 0");
}

.zmiqfrnyd {
  d: path("M6.5 5.5V2.75h7V5.5m4.5 14q5.25-8.25 0-16.5m-8 18v-7.5m-1.5-1.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
