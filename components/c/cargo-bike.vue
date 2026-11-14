<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h_m2y5b_z"/><path class="bvp0d7bwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cargo-bike" /></template>
<style>
.bvp0d7bwj {
  d: path("M5 17.5L9.5 11l2.5 6.5h7m-5.25-12h3.5A1.75 1.75 0 0 1 19 7.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-3.5A1.75 1.75 0 0 1 12 9.75v-2.5a1.75 1.75 0 0 1 1.75-1.75");
}

.h_m2y5b_z {
  d: path("M2 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m14 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
