<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fxyvsab-e"/><path class="npenpvb6u"/><path class="ap7tcjbly"/><path class="vxi-y-5ue"/><path class="dpd39d9rw"/><path class="k44ucwlod"/><path class="tgth1rbuy"/><path class="wxng3f21w"/><path class="jdxsdlola"/><path class="awxqv1b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:carbon-footprint-duotone-bold" /></template>
<style>
.ap7tcjbly {
  fill: currentColor;
  d: path("M10 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.awxqv1b4c {
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dpd39d9rw {
  fill: currentColor;
  d: path("M17 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.fxyvsab-e {
  fill: currentColor;
  d: path("M7 11a5 5 0 0 1 10 0v6a5 5 0 0 1 -10 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jdxsdlola {
  d: path("M14 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.k44ucwlod {
  d: path("M7 11a5 5 0 0 1 10 0v6a5 5 0 0 1 -10 0Z");
}

.npenpvb6u {
  fill: currentColor;
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.tgth1rbuy {
  d: path("M6 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vxi-y-5ue {
  fill: currentColor;
  d: path("M14 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wxng3f21w {
  d: path("M10 3.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
