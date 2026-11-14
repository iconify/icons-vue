<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i4uy5doyi"/><path class="r5e3en8-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardboard-model" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4uy5doyi {
  d: path("M4.5 10h10a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-10A1.5 1.5 0 0 1 3 20v-8.5A1.5 1.5 0 0 1 4.5 10M16 10l4-3v11.5l-4 3M3 10l4-3h13");
}

.r5e3en8-p {
  d: path("M3 10V4.5L6.75 3L7 7");
}

</style>
