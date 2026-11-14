<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tpmxkdvtz"/><path class="mvtbsmr2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bug-play" /></template>
<style>
.mvtbsmr2z {
  d: path("M6.25 6.25a2.75 2.75 0 0 1 5.5 0M9 5.5V18M4 9.5H2.25M4 13H2.25M14 9.5h1.75M17 16l4.75 2.75L17 21.5Z");
}

.tpmxkdvtz {
  d: path("M4 10.5a5 5 0 0 1 10 0V13a5 5 0 0 1-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
