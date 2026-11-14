<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iv1ym1byx"/><path class="oe6n3qwpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lamp-replacement" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iv1ym1byx {
  d: path("M3.5 21.5h6m-3 0V7a4 4 0 0 1 4-4h3v3");
}

.oe6n3qwpr {
  d: path("M10.5 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0m4.5 7.25h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
