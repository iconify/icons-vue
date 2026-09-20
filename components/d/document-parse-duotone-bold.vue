<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n7l2ayblh"/><path class="h4mbgmbqx"/><path class="bwrecrsdv"/><path class="dm6j51bgi"/><path class="v04-rubun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-parse-duotone-bold" /></template>
<style>
.bwrecrsdv {
  d: path("M15 14h4");
}

.dm6j51bgi {
  d: path("m16 11 3 3 -3 3");
}

.h4mbgmbqx {
  d: path("M12 2H5v16h8");
}

.n7l2ayblh {
  fill: currentColor;
  d: path("M14 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
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

.v04-rubun {
  d: path("M14 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
