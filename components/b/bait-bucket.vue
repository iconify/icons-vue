<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lg_4u-b-q"/><path class="sfli26bbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bait-bucket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg_4u-b-q {
  d: path("M6.964 8h10.072a1.75 1.75 0 0 1 1.739 1.951l-1.096 9.5A1.75 1.75 0 0 1 15.94 21H8.06a1.75 1.75 0 0 1-1.739-1.549l-1.096-9.5A1.75 1.75 0 0 1 6.964 8");
}

.sfli26bbm {
  d: path("M5 8c0-5.5 14-5.5 14 0M5.5 11.5h13m-8.5 4h.01m3.99 0h.01");
}

</style>
