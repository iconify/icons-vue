<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="ijy_9ib0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:allergen-fish" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijy_9ib0t {
  d: path("M6.5 12c2-3.25 6.5-3.25 8.5 0c-2 3.25-6.5 3.25-8.5 0m9.875-1.125za.842.842 0 0 1 1.375.652v.946a.842.842 0 0 1-1.375.652a1.454 1.454 0 0 1 0-2.25");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
