<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eztgfyb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:legal-ai" /></template>
<style>
.eztgfyb8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6h15m-7.5-3v16.5m-2.75 0H14M4.75 6L2.5 12.5a2.25 2.25 0 0 0 4.5 0Zm13 0l-2.25 6.5a2.25 2.25 0 0 0 4.5 0Zm.75 9c0 2.5 1 3.5 3.5 3.5c-2.5 0-3.5 1-3.5 3.5c0-2.5-1-3.5-3.5-3.5c2.5 0 3.5-1 3.5-3.5Z");
}

</style>
