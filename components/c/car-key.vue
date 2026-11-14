<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zen0m6phi"/><path class="bvdfb8bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-key" /></template>
<style>
.bvdfb8bwq {
  d: path("M5.25 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zen0m6phi {
  d: path("M3.5 7H11a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H3.5a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1Zm8.5 3h8l1.5 1.5v2h-3v2h-3v-2H12");
}

</style>
