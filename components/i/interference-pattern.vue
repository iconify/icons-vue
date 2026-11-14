<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ok0p5z5ai"/><path class="k9t7m5aoi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:interference-pattern" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k9t7m5aoi {
  d: path("M2.5 12c1.5 6 3.25 6 4.75 0S10.5 6 12 12s3.25 6 4.75 0S20 6 21.5 12");
}

.ok0p5z5ai {
  d: path("M2.5 12C4 6 5.75 6 7.25 12s3.25 6 4.75 0s3.25-6 4.75 0s3.25 6 4.75 0");
}

</style>
