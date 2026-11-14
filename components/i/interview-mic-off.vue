<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl4bmz33f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-mic-off" /></template>
<style>
.vl4bmz33f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM3 21.5c0-4 3-6.25 6.5-6.25a7.6 7.6 0 0 1 2.135.299M16 3h3.5v6H16Zm1.75 6v3m-2.25 3.5l5 5m0-5l-5 5");
}

</style>
