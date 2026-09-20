<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="koyutzhan"/><path class="ky7fjq4zo"/><path class="ujq9q6pvr"/><path class="ttpxlcc5b"/><path class="wfmdw-bov"/><path class="m3ubefbgj"/><path class="z55just5o"/><path class="qjx5s3xna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ingress-k8s-duotone-bold" /></template>
<style>
.koyutzhan {
  fill: currentColor;
  d: path("M3 13a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ky7fjq4zo {
  fill: currentColor;
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m3ubefbgj {
  d: path("M3 13a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.qjx5s3xna {
  d: path("M15 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ttpxlcc5b {
  d: path("M12 3v3.5");
}

.ujq9q6pvr {
  fill: currentColor;
  d: path("M15 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wfmdw-bov {
  d: path("M9.5 4 12 6.5 14.5 4");
}

.z55just5o {
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
