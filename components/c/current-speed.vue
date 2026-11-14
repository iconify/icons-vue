<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m668x1b0w"/><path class="cdodavbuc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:current-speed" /></template>
<style>
.cdodavbuc {
  d: path("M10.5 14a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm2.5-1l3.5-3.5");
}

.m668x1b0w {
  d: path("M3.75 18.75a9.5 9.5 0 1 1 16.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
