<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wprabmufl"/><path class="dpyutov5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-basket" /></template>
<style>
.dpyutov5f {
  d: path("M13.75 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wprabmufl {
  d: path("M6.25 17.25a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m4.25 0L7.75 4.5m-3.25 0h5M12.87 6h5.76a1.5 1.5 0 0 1 1.464 1.825l-.333 1.5a1.5 1.5 0 0 1-1.464 1.175h-5.094a1.5 1.5 0 0 1-1.464-1.175l-.333-1.5A1.5 1.5 0 0 1 12.87 6");
}

</style>
