<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sz7-z2bxg"/><path class="w28ce8bfd"/><path class="h_660k-uu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:face-blush" /></template>
<style>
.h_660k-uu {
  fill: currentColor;
  d: path("M5.25 13a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0m10.5 0a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sz7-z2bxg {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m6-2.75h.01m6.99 0h.01");
}

.w28ce8bfd {
  d: path("M9.75 16q2.25 2.75 4.5 0");
}

</style>
