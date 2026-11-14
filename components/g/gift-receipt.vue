<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jusjcubrk"/><path class="a4qocsldh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gift-receipt" /></template>
<style>
.a4qocsldh {
  d: path("M12 10.5c-1.25-3.25-4.75-3.25-4.75-1s3.5 3 4.75 1m0 0c1.25-3.25 4.75-3.25 4.75-1s-3.5 3-4.75 1m-.75 2L9.5 16m3.25-3.5L14.5 16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jusjcubrk {
  d: path("M5.25 2.5h13.5a1.75 1.75 0 0 1 1.75 1.75v14.984a1.17 1.17 0 0 1-1.75 1.016l-.882-.504a1.75 1.75 0 0 0-1.736 0l-1.764 1.008a1.75 1.75 0 0 1-1.736 0l-1.764-1.008a1.75 1.75 0 0 0-1.736 0l-1.693.967A1.75 1.75 0 0 1 5.6 20.65l-1.321-.88a1.75 1.75 0 0 1-.779-1.457V4.25A1.75 1.75 0 0 1 5.25 2.5");
}

</style>
