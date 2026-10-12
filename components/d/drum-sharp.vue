<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vy-rjz-ny"/><path class="i7uoh366i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drum-sharp" /></template>
<style>
.i7uoh366i {
  d: path("M3.75 10a8.25 3.25 0 0 0 16.5 0M7.5 13.1v7m4.5-6.85v8m4.5-8.15v7M4.75 2.75l4.5 4.5m10-4.5l-4.5 4.5");
}

.vy-rjz-ny {
  d: path("M3.75 10a8.25 3.25 0 0 1 16.5 0v7.5c0 2.1-3.7 3.75-8.25 3.75S3.75 19.6 3.75 17.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
