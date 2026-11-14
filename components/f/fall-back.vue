<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l5_bi3bag"/><path class="aarn-iblx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fall-back" /></template>
<style>
.aarn-iblx {
  d: path("M9.25 16.75L11.5 19l-2.25 2.25M11.5 7.5v4L14 13m1.5 8.5q0-6 6-6q0 6-6 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5_bi3bag {
  d: path("M11.5 19a7.5 7.5 0 1 1 7.5-7.5");
}

</style>
