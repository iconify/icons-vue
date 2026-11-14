<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px2nex24k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-detector" /></template>
<style>
.px2nex24k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.5v15m-1.75-14L10 5l1.75-1.5m-3.5 13L10 15l1.75 1.5M16.5 6.25l-13 7.5m11.25-8.5l-.5 2.25l2.25.75m-13 3.5l2.25.75l-.5 2.25M3.5 6.25l11.694 6.746M5.25 5.25l.5 2.25l-2.25.75m13 3.5l-2.25.75l.223 1.004m.777 3.996a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4 1.75L21 21");
}

</style>
