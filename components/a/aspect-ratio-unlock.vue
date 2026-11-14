<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wzzibubvr"/><path class="ddsjmr5xp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aspect-ratio-unlock" /></template>
<style>
.ddsjmr5xp {
  d: path("M5.75 11V7.75H9m4 6.75h8.5v7H13Zm2.25 0V12a2.25 2.25 0 0 1 4.5-.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wzzibubvr {
  d: path("M10.25 18.5H4.5a2 2 0 0 1-2-2v-10a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2v1");
}

</style>
