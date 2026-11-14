<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gec5zxb8c"/><path class="jx2r-boip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coin-pouch" /></template>
<style>
.gec5zxb8c {
  d: path("M9.5 11c-6 2-6.5 10-1 10h7c5.5 0 5-8-1-10Zm2.5 0l-1.5 3m1.5-3l1.5 3M8 5a4 1.75 0 1 0 8 0a4 1.75 0 1 0-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jx2r-boip {
  d: path("M8 5v2a4 1.75 0 0 0 8 0V5");
}

</style>
