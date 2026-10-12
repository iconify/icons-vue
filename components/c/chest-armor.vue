<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x4huqxfkr"/><path class="p1erp238d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chest-armor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1erp238d {
  d: path("M5.5 16c4 1.75 9 1.75 13 0");
}

.x4huqxfkr {
  d: path("M6.5 3.25H9C9.5 5 10.5 6 12 6s2.5-1 3-2.75h2.5c.25 2.75 1.25 4.5 3.25 5.25l-1 6.5C19.5 18.5 16 21.25 12 21.25S4.5 18.5 4.25 15l-1-6.5c2-.75 3-2.5 3.25-5.25M12 9v5");
}

</style>
