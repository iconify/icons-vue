<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="svuooibzi"/><path class="g6-r9cv9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-loop-back" /></template>
<style>
.g6-r9cv9w {
  d: path("M8.58 7.66a6.75 6.75 0 1 1 0 8.68l-.96-1.15m0 0l-.3 3.49m.3-3.49l3.49.3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.svuooibzi {
  cx: 4.75px;
  cy: 12px;
  r: 2px;
}

</style>
