<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pj73u_bkl"/><path class="ohlo6t-zz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hedgehog-house" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohlo6t-zz {
  d: path("M10 12.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7 9L5 20l2 1.5L9 20l2 1.5l2-1.5l2 1.5l2-1.5l2 1.5l2-1.5");
}

.pj73u_bkl {
  d: path("m5.334 8.722l4.875-4.55a2.625 2.625 0 0 1 3.582 0l4.875 4.55a2.63 2.63 0 0 1 .834 1.919v3.984a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 4.5 14.625v-3.984a2.63 2.63 0 0 1 .834-1.919");
}

</style>
