<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0l35cb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-row-letter" /></template>
<style>
.g0l35cb1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16v-4.25a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3V16M5.5 16h13v3h-13Zm-2.75-4v9.5m18.5-9.5v9.5M10 6V2.5h5.5l-1.75 1.75L15.5 6Z");
}

</style>
