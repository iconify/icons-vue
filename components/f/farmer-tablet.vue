<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zxp9v3b8l"/><path class="gicz6cbff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farmer-tablet" /></template>
<style>
.gicz6cbff {
  d: path("M12 10.5c0-2.5-1.5-4-4.25-4c0 2.5 1.75 4 4.25 4m0 0c0-2.5 1.5-4 4.25-4c0 2.5-1.75 4-4.25 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zxp9v3b8l {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5m1.625 16h3m-1.5-3v-5");
}

</style>
