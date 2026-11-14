<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tsxx4ebxd"/><path class="l8rrj4bmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dry-eye" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8rrj4bmr {
  d: path("M7.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 0h.01M18 14c1.75 2 3 3.5 3 5c0 1.6-1.4 2.75-3 2.75S15 20.6 15 19c0-1.5 1.25-3 3-5");
}

.tsxx4ebxd {
  d: path("M2.5 9.5c2.25-3.5 5-5 7.5-5s5.25 1.5 7.5 5c-2.25 3.5-5 5-7.5 5s-5.25-1.5-7.5-5");
}

</style>
