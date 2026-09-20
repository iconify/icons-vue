<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w3hyiobto"/><path class="g4pfarntv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bookmark-label-outline-thin" /></template>
<style>
.g4pfarntv {
  d: path("M10 10.5h4v6l-2 -2 -2 2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w3hyiobto {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

</style>
