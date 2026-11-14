<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf8_v2b4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-seats" /></template>
<style>
.rf8_v2b4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 14V8a2 2 0 0 1 2-2H7a2 2 0 0 1 2 2v6m0 0V8a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v6m0 0V8a2 2 0 0 1 2-2h1.5a2 2 0 0 1 2 2v6m-18 0h19v3h-19Zm2 3v3.5m15-3.5v3.5");
}

</style>
