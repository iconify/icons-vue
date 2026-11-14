<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_bxed9ty"/><path class="bsluc0s4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:house-sold" /></template>
<style>
.bsluc0s4p {
  d: path("M16 6.25V3h2.5v5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_bxed9ty {
  fill: currentColor;
  d: path("M3 10.5L12 3l9 7.5V21H3Zm3.25 4.25L10.5 19l7.25-7.25l-2.5-2.5L10.5 14l-1.75-1.75Z");
}

</style>
