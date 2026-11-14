<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yru40db1x"/><path class="di9td_-ow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bot-happy" /></template>
<style>
.di9td_-ow {
  d: path("M7 13.5a1.5 1.5 0 0 1 3 0m4 0a1.5 1.5 0 0 1 3 0m-7 3c1 1.5 3 1.5 4 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yru40db1x {
  d: path("M5.5 7h13a2 2 0 0 1 2 2v9.5a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2ZM12 2.5V7");
}

</style>
