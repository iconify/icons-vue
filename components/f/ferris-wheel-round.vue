<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st3qpmdax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ferris-wheel-round" /></template>
<style>
.st3qpmdax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0m7 2l-6 9m6-9l6 9M4 21h16m-6-11h5m-9 0H5m-1 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m2.05-4.95a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9.9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0M18 10a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
