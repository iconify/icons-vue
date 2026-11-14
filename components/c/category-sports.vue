<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="kmrllabfu"/><path class="yrrgopbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:category-sports" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmrllabfu {
  fill: currentColor;
  d: path("m12.915 9.204l1.489 1.145a1.5 1.5 0 0 1 .508 1.664l-.57 1.711a1.5 1.5 0 0 1-1.423 1.026h-1.838a1.5 1.5 0 0 1-1.423-1.026l-.57-1.711a1.5 1.5 0 0 1 .508-1.664l1.489-1.145a1.5 1.5 0 0 1 1.83 0");
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

.yrrgopbad {
  d: path("M12 8.5v-3m0 0l3.5-2.25M12 5.5L8.5 3.25M15.25 11l3-1m0 0l1-4m-1 4l3.25 2.75m-7.5 2l1.75 2.5m0 0L20 17m-4.25.25l-1.5 4M10 14.75l-1.75 2.5m0 0L4 17m4.25.25l1.5 4M8.75 11l-3-1m0 0l-1-4m1 4L2.5 12.75");
}

</style>
