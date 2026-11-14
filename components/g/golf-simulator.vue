<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s3_-g4bjz"/><path class="hc13241cn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-simulator" /></template>
<style>
.hc13241cn {
  d: path("m15 6l3.5 1.75L15 9.5Z");
}

.s3_-g4bjz {
  d: path("M11 2.5h10.5v15H11Zm-8 4a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 5.25V16M3 21.5L5.5 16L8 21.5M15 6v8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
