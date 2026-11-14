<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g15ay4b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lost-hiker" /></template>
<style>
.g15ay4b-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm1.5 5l-1.5 4.75M4.5 21l3.25-6.5L11.5 21M5 12.5L8.75 11L12 13.5m3.75 1.5A2.25 2.25 0 1 1 18 17.25v1.25m0 2.75h.01");
}

</style>
