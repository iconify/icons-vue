<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbsfbub6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audio-ducking" /></template>
<style>
.fbsfbub6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7v10M7 10.5v3m3.5-3v3M14 7v10m5.5-14.5v11m0 4v4m-2-6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
