<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lia79qp9o"/><path class="tos1z6bkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:action-camera" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lia79qp9o {
  d: path("M7.375 6h9.25A4.375 4.375 0 0 1 21 10.375v4.25A4.375 4.375 0 0 1 16.625 19h-9.25A4.375 4.375 0 0 1 3 14.625v-4.25A4.375 4.375 0 0 1 7.375 6");
}

.tos1z6bkw {
  d: path("M6 12.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m10.5-3h.5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-.5A1.5 1.5 0 0 1 15 11a1.5 1.5 0 0 1 1.5-1.5m-1-6h3");
}

</style>
