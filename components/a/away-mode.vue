<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2vwigwwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:away-mode" /></template>
<style>
.g2vwigwwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21V11L7 6.5l4.5 4.5v10Zm14-16.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM18 9.5L16.75 15m-2.25 6l2.25-6l2.5 3l-.5 3M15 12l2.5-1.75L20 12.5");
}

</style>
