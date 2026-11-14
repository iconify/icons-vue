<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fcumicb9d"/><path class="kg51jz0ld"/><path class="r2yndgt2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-solar-lights" /></template>
<style>
.fcumicb9d {
  d: path("M5.608 2.5h12.784a1.5 1.5 0 0 1 1.434 1.059l1.077 3.5A1.5 1.5 0 0 1 19.469 9H4.531a1.5 1.5 0 0 1-1.434-1.941l1.077-3.5A1.5 1.5 0 0 1 5.608 2.5M12 12v9.5m-2.5-19L8.75 9m5.75-6.5l.75 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kg51jz0ld {
  fill: currentColor;
  d: path("M11.5 9h1a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 11.5 9");
}

.r2yndgt2i {
  d: path("M7.25 12.25L5.5 14.5m11.25-2.25l1.75 2.25");
}

</style>
