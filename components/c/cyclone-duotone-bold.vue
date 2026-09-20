<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="k5uwieaec"/><path class="uahsis41g"/><path class="dnuzbjvda"/><path class="i3v5drdpw"/><path class="bo51iypxr"/><path class="e771rwjjh"/><path class="xysie__pz"/><path class="se-pwqb_b"/><path class="km3h1bbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cyclone-duotone-bold" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dnuzbjvda {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 5h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e771rwjjh {
  d: path("M9 17A5 5 0 0 1 9 7");
}

.i3v5drdpw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 19h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k5uwieaec {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 17A5 5 0 0 1 9 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km3h1bbzc {
  d: path("M15 19h7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.se-pwqb_b {
  d: path("M2 5h7");
}

.uahsis41g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 7a5 5 0 0 1 0 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xysie__pz {
  d: path("M15 7a5 5 0 0 1 0 10");
}

</style>
