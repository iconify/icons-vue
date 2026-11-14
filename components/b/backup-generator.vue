<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a_all4asq"/><path class="nta6tybyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backup-generator" /></template>
<style>
.a_all4asq {
  d: path("M3 7h18v12H3Zm2 0V4h14v3");
}

.nta6tybyw {
  d: path("M13 9.75L10 13h4l-3 3.25M5.5 19v2m13-2v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
