<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m8vy5un_m"/><path class="p1953xb7s"/><path class="ri3harcsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bone-scan" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8vy5un_m {
  d: path("M6.5 9.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.p1953xb7s {
  d: path("M8.25 7.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m5 8.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.ri3harcsg {
  d: path("M15 14.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M9.75 9.75l4.5 4.5M2.5 6.5v-4h4m11 0h4v4m0 11v4h-4m-11 0h-4v-4");
}

</style>
