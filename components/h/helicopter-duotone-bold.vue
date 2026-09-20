<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ww1ug7bih"/><path class="y_6hdgy9a"/><path class="jtrmczbpr"/><path class="sb7rl7wyu"/><path class="dksaywbrx"/><path class="m0f5ny81l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:helicopter-duotone-bold" /></template>
<style>
.dksaywbrx {
  d: path("M15 11h6V6");
}

.jtrmczbpr {
  d: path("M2 6h14");
}

.m0f5ny81l {
  d: path("M5 20h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sb7rl7wyu {
  d: path("M9 6v3");
}

.ww1ug7bih {
  fill: currentColor;
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y_6hdgy9a {
  d: path("M3 11a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
