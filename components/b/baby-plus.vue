<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="sulf22bsc"/><path class="p7mm1oxkk"/><path class="pkxclebiu"/><path class="qajrzkb3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-plus" /></template>
<style>
.p7mm1oxkk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.75c-1.1 0-1.75.75-1.75 1.5s.6 1.25 1.25 1.25");
}

.pkxclebiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11.5h.01m5.99 0h.01");
}

.qajrzkb3t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 15.5c1.25 1 3.25 1 4.5 0");
}

.sulf22bsc {
  cx: 12px;
  cy: 12.5px;
  r: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
