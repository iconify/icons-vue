<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7nksvcwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clapperboard-plus" /></template>
<style>
.m7nksvcwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 20.5H3v-11h18v5.7M3.25 9.5L2.5 6l17-3l.75 3.5Zm5-4.75L10 8.25m3.5-4.5l1.75 3.5M18 15v6m-3-3h6");
}

</style>
