<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aaorrgb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diffusion-scrim" /></template>
<style>
.aaorrgb1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h11v13h-11Zm2.5 13l-2.5 6m8.5-6l2.5 6M3.5 5q-1.5 4 0 8m17-8q1.5 4 0 8");
}

</style>
