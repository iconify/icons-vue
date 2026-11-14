<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9g224bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:groom-bowtie-head" /></template>
<style>
.m9g224bmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 8.25a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0ZM12 19l-5-2.5v5Zm0 0l5-2.5v5Z");
}

</style>
