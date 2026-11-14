<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k6zx65bsb"/><path class="pgiqog0it"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-remote" /></template>
<style>
.k6zx65bsb {
  d: path("M7.5 9.5h9v12h-9Z");
}

.pgiqog0it {
  d: path("M10.25 14.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-.725-7.225a3.5 3.5 0 0 1 4.95 0M7.05 4.55a7 7 0 0 1 9.9 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
