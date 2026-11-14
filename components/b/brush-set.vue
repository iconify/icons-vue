<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciddo369g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brush-set" /></template>
<style>
.ciddo369g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 13h17v8.5h-17Zm3 0V8.5M5 8.5C5 6.5 6.5 4 6.5 4S8 6.5 8 8.5Zm7 4.5V7m-1.5 0c0-2 1.5-4.5 1.5-4.5S13.5 5 13.5 7Zm7 6V8.5m-1.5 0c0-2 1.5-4.5 1.5-4.5S19 6.5 19 8.5Z");
}

</style>
