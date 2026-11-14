<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bwkn0ybci"/><path class="z6vv9im_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-trap" /></template>
<style>
.bwkn0ybci {
  d: path("M5 2.5h1.5A1.5 1.5 0 0 1 8 4v16a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 20V4A1.5 1.5 0 0 1 5 2.5m5.625 3h7.25A2.625 2.625 0 0 1 20.5 8.125v3.75a2.625 2.625 0 0 1-2.625 2.625h-7.25A2.625 2.625 0 0 1 8 11.875v-3.75A2.625 2.625 0 0 1 10.625 5.5M3.5 10H8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6vv9im_k {
  d: path("M12.25 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4.736 7.518a8 8 0 0 1-5.472 0");
}

</style>
