<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f1zgmab8x"/><path class="taxqp9b1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:captions-edit" /></template>
<style>
.f1zgmab8x {
  d: path("M12.5 19h-10V5h19v8.1");
}

.taxqp9b1b {
  d: path("M10 10.25a2 2 0 1 0 0 3.5m6.5-3.5a2 2 0 1 0 0 3.5m-1.5 7.5l.25-2L19.5 15l1.75 1.75L17 21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
