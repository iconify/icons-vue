<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pos7ej6th"/><path class="xpkehhckr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jump-rope" /></template>
<style>
.pos7ej6th {
  d: path("M5 3.5V7c0 13 14 13 14 0V3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xpkehhckr {
  d: path("M3.5 2.5h3V8h-3Zm14 0h3V8h-3Z");
}

</style>
