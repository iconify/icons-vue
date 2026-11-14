<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4fsweg7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eel" /></template>
<style>
.z4fsweg7z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.25c1-1.5 2-2.5 3-2.5c2 0 2.5 5 4 6.5s2 3.25 3.5 3.25c2 0 3-1.5 4.5-1.75a.75.75 0 0 1 .5 1.25c-1.75 1-3 5-5 5c-2.5 0-3-2.5-4.5-4c-1.25-1.5-2-4.25-3-4.25S6.25 13.5 5 14.5c-2.5 0-2.5-7.25 0-7.25Zm.5 2.5h.01");
}

</style>
