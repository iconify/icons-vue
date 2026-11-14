<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y64-oob1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baptism-shell" /></template>
<style>
.y64-oob1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 4l11-1a3.5 3.5 0 0 1-1.25 6.25a3.5 3.5 0 0 1-4.5 4.5A3.5 3.5 0 0 1 3 15Zm4.5 2.5l5.25 2.75M6.5 8.5l2.75 5.25m8.25.25q2.5 3.5 2.5 4.25a2.5 2.5 0 0 1-5 0q0-.75 2.5-4.25Z");
}

</style>
