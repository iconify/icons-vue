<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku5ffwb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airport-lounge" /></template>
<style>
.ku5ffwb3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 6h8M13 6l-2.25-3.25M13 6l-2.25 3.25M9.25 6l-1-1.5m1 1.5l-1 1.5M2.75 13a1.75 1.75 0 0 1 3.5 0v1.5h11.5V13a1.75 1.75 0 0 1 3.5 0v5a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Zm2.75 7v1.25m13-1.25v1.25");
}

</style>
