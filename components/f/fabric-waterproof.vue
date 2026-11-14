<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef9xk87np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fabric-waterproof" /></template>
<style>
.ef9xk87np {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 14h15.5a3 3 0 0 1 0 6H3Zm0 3h15.5M8 4.5c-1.5 2-2.5 3.25-2.5 4.25a2.5 2.5 0 0 0 5 0c0-1-1-2.25-2.5-4.25Zm7.5 0C14 6.5 13 7.75 13 8.75a2.5 2.5 0 0 0 5 0c0-1-1-2.25-2.5-4.25Z");
}

</style>
