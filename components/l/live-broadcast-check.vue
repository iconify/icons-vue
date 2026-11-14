<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoue20wkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:live-broadcast-check" /></template>
<style>
.xoue20wkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.3 15.5H2.5v-12H16v11.8m0-7.8l5.5-3v7.835m-2.05 1.047L16 11.5m-4.5-4h.01M14.75 18l2 2L21 15.75");
}

</style>
