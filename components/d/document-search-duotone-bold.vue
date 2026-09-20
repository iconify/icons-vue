<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="o27kfibmc"/><path class="abnm6smsv"/><path class="b1ycfzbls"/><path class="agblgzlbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-search-duotone-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.agblgzlbb {
  d: path("M13.5 13.5 16 16");
}

.b1ycfzbls {
  d: path("M8.5 11.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.o27kfibmc {
  fill: currentColor;
  d: path("M8.5 11.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
