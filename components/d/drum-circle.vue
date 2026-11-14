<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gus1t0btx"/><path class="lobcdr0mg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drum-circle" /></template>
<style>
.gus1t0btx {
  d: path("M7.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM2 16.75a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Zm11.5 0a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

.lobcdr0mg {
  d: path("M10.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-5.75 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11.5 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
