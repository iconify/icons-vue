<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ur-n4_fxh"/><path class="nw8-8vb0d"/><path class="cxo2jiicg"/><path class="de90k9bog"/><path class="iedujiqkb"/><path class="a-9s6wb0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:game-map-duotone-bold" /></template>
<style>
.a-9s6wb0y {
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.cxo2jiicg {
  fill: currentColor;
  d: path("M15 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.de90k9bog {
  d: path("M3 6c2 -1 4 2 6 2s4 -3 6 -3 4 3 6 1v12c-2 2 -4 -1 -6 -1s-4 3 -6 3 -4 -3 -6 -2Z");
}

.iedujiqkb {
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nw8-8vb0d {
  fill: currentColor;
  d: path("M7 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
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

.ur-n4_fxh {
  fill: currentColor;
  d: path("M3 6c2 -1 4 2 6 2s4 -3 6 -3 4 3 6 1v12c-2 2 -4 -1 -6 -1s-4 3 -6 3 -4 -3 -6 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
