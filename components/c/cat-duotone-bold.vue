<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l8ayoxl9v"/><path class="vijzu2b4y"/><path class="zo-oy-vgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cat-duotone-bold" /></template>
<style>
.l8ayoxl9v {
  fill: currentColor;
  d: path("M5 13V5l4 4c1 -0.5 5 -0.5 6 0l4 -4v8c1 2 1 5 -1 7S8 22 6 20s-2 -5 -1 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vijzu2b4y {
  d: path("M5 13V5l4 4c1 -0.5 5 -0.5 6 0l4 -4v8c1 2 1 5 -1 7S8 22 6 20s-2 -5 -1 -7");
}

.zo-oy-vgw {
  d: path("m10 15 2 2 2 -2");
}

</style>
