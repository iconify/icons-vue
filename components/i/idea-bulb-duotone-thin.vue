<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b32qokucr"/><path class="usr9unc6p"/><path class="x3sflacnk"/><path class="p937wxhzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:idea-bulb-duotone-thin" /></template>
<style>
.b32qokucr {
  fill: currentColor;
  d: path("M8 12a6 6 0 1 1 8 0v3H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p937wxhzi {
  d: path("M10 21h4");
}

.usr9unc6p {
  d: path("M8 12a6 6 0 1 1 8 0v3H8Z");
}

.x3sflacnk {
  d: path("M9 18h6");
}

</style>
