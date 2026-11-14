<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncss_n9-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:api-mock" /></template>
<style>
.ncss_n9-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5v-1a3 3 0 0 1 3-3h1m3.5 0h4m3.5 0h1a3 3 0 0 1 3 3v1m0 3.5v4m0 3.5v1a3 3 0 0 1-3 3h-1m-3.5 0h-4m-3.5 0h-1a3 3 0 0 1-3-3v-1m0-3.5v-4M10 7h-.5A1.5 1.5 0 0 0 8 8.5v2A1.5 1.5 0 0 1 6.5 12A1.5 1.5 0 0 1 8 13.5v2A1.5 1.5 0 0 0 9.5 17h.5m4-10h.5A1.5 1.5 0 0 1 16 8.5v2a1.5 1.5 0 0 0 1.5 1.5a1.5 1.5 0 0 0-1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5H14");
}

</style>
