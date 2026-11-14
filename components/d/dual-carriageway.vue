<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl5qu530j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dual-carriageway" /></template>
<style>
.gl5qu530j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5v19m19-19v19m-11-19h3v19h-3Zm-4 1V20M5 18.5L6.5 20L8 18.5m9.5 2V4M16 5.5L17.5 4L19 5.5");
}

</style>
