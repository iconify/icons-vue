<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g2r3eubpu"/><path class="ke028acry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:banana-duotone-bold" /></template>
<style>
.g2r3eubpu {
  fill: currentColor;
  d: path("M4 7c0 9 6 14 16 12 -7 -2 -11 -6 -11 -13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ke028acry {
  d: path("M4 7c0 9 6 14 16 12 -7 -2 -11 -6 -11 -13Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
