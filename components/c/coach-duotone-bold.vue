<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vtfcgd5bf"/><path class="swwpttflz"/><path class="a8b_i2bss"/><path class="f22ajzb8t"/><path class="vhnbtvbtn"/><path class="x1w930bwh"/><path class="a_-b16kjh"/><path class="yih0nfb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coach-duotone-bold" /></template>
<style>
.a_-b16kjh {
  d: path("M15 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.a8b_i2bss {
  fill: currentColor;
  d: path("M15 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f22ajzb8t {
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.swwpttflz {
  fill: currentColor;
  d: path("M5 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.vtfcgd5bf {
  fill: currentColor;
  d: path("M3 4a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.x1w930bwh {
  d: path("M5 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.yih0nfb7c {
  d: path("M3 14h18");
}

</style>
