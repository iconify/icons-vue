<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o1978yv-q"/><path class="e9i-mpbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:autoplay-duocolor-round" /></template>
<style>
.e9i-mpbsf {
  d: path("M20 16a8.944 8.944 0 1 1 0-8m-4 0h4V4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o1978yv-q {
  stroke-opacity: 0.4;
  d: path("M10 12V8l6 4l-6 4z");
}

</style>
