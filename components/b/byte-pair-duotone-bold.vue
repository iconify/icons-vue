<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x47uatb1d"/><path class="p0lbyib3y"/><path class="vfo57uyzf"/><path class="q2fp4ccin"/><path class="p-6zwabto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:byte-pair-duotone-bold" /></template>
<style>
.p-6zwabto {
  d: path("M6 14v3h12v-3");
}

.p0lbyib3y {
  fill: currentColor;
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.q2fp4ccin {
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vfo57uyzf {
  d: path("M3 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.x47uatb1d {
  fill: currentColor;
  d: path("M3 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
