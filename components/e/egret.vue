<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="enfsp8bdj"/><path class="vy3tw574w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:egret" /></template>
<style>
.enfsp8bdj {
  d: path("m21.5 5.5l-4.75-1.75c-.5-.75-1.25-1.25-2-1.25c-1.25 0-2 1-2 2.25S13.5 7 13 8.5c-2 0-5 .5-7 1.75L2.75 13c2.75.75 5.25 1.25 7.75 1.25c3.5 0 5.75-1.75 5.75-4c0-1.75-1-3.25 0-4.5ZM9 14.25v7.25m3-7.5v7.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vy3tw574w {
  d: path("M6 10.25c-1.5-.25-2.75.25-3.5 1.25");
}

</style>
