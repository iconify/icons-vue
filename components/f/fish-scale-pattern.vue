<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wn5wggf2r"/><path class="e_h-7bcrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-scale-pattern" /></template>
<style>
.e_h-7bcrr {
  d: path("M9.5 9.5q2 2.5 0 5m3.5-5q2 2.5 0 5m-7-3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wn5wggf2r {
  d: path("M2.5 12c3.5-7.5 12-7.5 15 0l4-4v8l-4-4c-3 7.5-11.5 7.5-15 0");
}

</style>
