<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldvf95bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:copper-ingot" /></template>
<style>
.ldvf95bph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.268 15.697l.833-2.5A1.75 1.75 0 0 1 5.761 12h12.478a1.75 1.75 0 0 1 1.66 1.197l.833 2.5A1.75 1.75 0 0 1 19.072 18H4.928a1.75 1.75 0 0 1-1.66-2.303m4-6l.833-2.5A1.75 1.75 0 0 1 9.761 6h4.478a1.75 1.75 0 0 1 1.66 1.197l.833 2.5A1.75 1.75 0 0 1 15.072 12H8.928a1.75 1.75 0 0 1-1.66-2.303");
}

</style>
