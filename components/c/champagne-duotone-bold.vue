<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="i4u9dxbqm"/><path class="bb278gpil"/><path class="kllnjy40b"/><path class="ytw5afb0h"/><path class="xtjp0b80d"/><path class="frofbtbej"/><path class="dxdpz6gbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:champagne-duotone-bold" /></template>
<style>
.bb278gpil {
  fill: currentColor;
  d: path("M14 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dxdpz6gbz {
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.frofbtbej {
  d: path("M14 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.i4u9dxbqm {
  fill: currentColor;
  d: path("M5 21v-8c0 -2 1 -3 1 -5V5h4v3c0 2 1 3 1 5v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kllnjy40b {
  fill: currentColor;
  d: path("M17 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.xtjp0b80d {
  d: path("M6 5V2h4v3");
}

.ytw5afb0h {
  d: path("M5 21v-8c0 -2 1 -3 1 -5V5h4v3c0 2 1 3 1 5v8Z");
}

</style>
