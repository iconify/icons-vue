<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uvytm8bsc"/><path class="n_3vzob0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:autoplay-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n_3vzob0n {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 16a8.944 8.944 0 1 1 0-8m-4 0h4V4m-10 8V8l6 4l-6 4z");
}

.uvytm8bsc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 12V8l6 4l-6 4Z");
}

</style>
