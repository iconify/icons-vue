<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctanx-boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-poop" /></template>
<style>
.ctanx-boz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21h13a2.75 2.75 0 0 0-1-5.25a2.75 2.75 0 0 0-2-4.75a2.75 2.75 0 0 0-3-4.5c0-1.5-.5-2.5-2-3c0 2-1.5 3-2.5 3.5a2.25 2.25 0 0 0 .5 4a2.75 2.75 0 0 0-2 4.75a2.75 2.75 0 0 0-1 5.25Zm1-5.25h11M8.5 11h7");
}

</style>
