<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm8pb0b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drag-drop-zone" /></template>
<style>
.bm8pb0b1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7V5.5a2 2 0 0 1 2-2H7m10 0h1.5a2 2 0 0 1 2 2V7m0 10v1.5a2 2 0 0 1-2 2H17m-10 0H5.5a2 2 0 0 1-2-2V17m7-13.5h3m-3 17h3m-10-10v3m17-3v3m-8.5-6v6m-2.75-2.75L12 13.5l2.75-2.75M8.5 16.5h7");
}

</style>
