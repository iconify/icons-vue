<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tlqg1hccg"/><path class="x9i7w9bkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bed-king" /></template>
<style>
.tlqg1hccg {
  d: path("M3.5 12V5a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v7m-18 0h19v5h-19Zm2 5v3.5m15-3.5v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9i7w9bkk {
  d: path("M6.5 8.5h4V12h-4Zm7 0h4V12h-4Z");
}

</style>
