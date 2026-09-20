<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vijzu2b4y"/><path class="zo-oy-vgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cat-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vijzu2b4y {
  d: path("M5 13V5l4 4c1 -0.5 5 -0.5 6 0l4 -4v8c1 2 1 5 -1 7S8 22 6 20s-2 -5 -1 -7");
}

.zo-oy-vgw {
  d: path("m10 15 2 2 2 -2");
}

</style>
