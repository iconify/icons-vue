<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rm_91rzkg"/><path class="l0m81fb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chip-dip" /></template>
<style>
.l0m81fb9x {
  d: path("M3 10a2 2 0 0 1 0 4M6.5 3v4M10 3v4m3.5-4v4M17 3v4M6.5 17v4m3.5-4v4m3.5-4v4m3.5-4v4");
}

.rm_91rzkg {
  d: path("M3 7h18v10H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
