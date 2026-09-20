<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dr0ex9erc"/><path class="rntvmcbgi"/><path class="txxjjstdk"/><path class="d-a_pubdj"/><path class="nziq0gact"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dustpan-duotone-bold" /></template>
<style>
.d-a_pubdj {
  d: path("M18 4v8");
}

.dr0ex9erc {
  fill: currentColor;
  d: path("M2 11h10c-0.5 4 -2 7 -3 10H5c-1 -3 -2.5 -6 -3 -10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nziq0gact {
  d: path("M15 12h6v4h-6Z");
}

.rntvmcbgi {
  fill: currentColor;
  d: path("M15 12h6v4h-6Z");
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

.txxjjstdk {
  d: path("M2 11h10c-0.5 4 -2 7 -3 10H5c-1 -3 -2.5 -6 -3 -10");
}

</style>
