<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b3xs-1ihq"/><path class="k267h_a7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-noticeboard" /></template>
<style>
.b3xs-1ihq {
  d: path("M5.5 3h13A3.5 3.5 0 0 1 22 6.5v6a3.5 3.5 0 0 1-3.5 3.5h-13A3.5 3.5 0 0 1 2 12.5v-6A3.5 3.5 0 0 1 5.5 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k267h_a7l {
  d: path("M6.25 5.75h11.5a1.5 1.5 0 0 1 1.5 1.5v4.5a1.5 1.5 0 0 1-1.5 1.5H6.25a1.5 1.5 0 0 1-1.5-1.5v-4.5a1.5 1.5 0 0 1 1.5-1.5M6 16v5.5M18 16v5.5");
}

</style>
