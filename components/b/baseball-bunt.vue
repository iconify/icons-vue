<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olspul6ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baseball-bunt" /></template>
<style>
.olspul6ny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6h7l11.5-1.75v6.5L10 9H3Zm9.5 11a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

</style>
