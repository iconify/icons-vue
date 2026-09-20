<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pfwplpb0a"/><path class="qux7qhbwn"/><path class="ungmwgbql"/><path class="u38qczjqj"/><path class="pwifkhr-v"/><path class="lw7cnobek"/><path class="xwbym4b8b"/><path class="srjp1meri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:headset-duotone-bold" /></template>
<style>
.lw7cnobek {
  d: path("M17 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.pfwplpb0a {
  fill: currentColor;
  d: path("M3 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pwifkhr-v {
  d: path("M3 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.qux7qhbwn {
  fill: currentColor;
  d: path("M17 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
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

.srjp1meri {
  d: path("M11.5 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u38qczjqj {
  d: path("M4 11a8 8 0 0 1 16 0");
}

.ungmwgbql {
  fill: currentColor;
  d: path("M11.5 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xwbym4b8b {
  d: path("M21 18v3h-6");
}

</style>
