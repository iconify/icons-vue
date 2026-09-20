<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h033mmb1s"/><path class="h68oqyb7w"/><path class="h8mw02bqq"/><path class="xp32bq_mk"/><path class="c7dgfu7wx"/><path class="n-z4jv76k"/><path class="qagp93bmg"/><path class="diaqyhfcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:darkroom-duotone-bold" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.diaqyhfcp {
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.h033mmb1s {
  fill: currentColor;
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h68oqyb7w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h8mw02bqq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v14h10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n-z4jv76k {
  d: path("M7 4v14h10V4");
}

.qagp93bmg {
  d: path("m9 14 3 -3 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xp32bq_mk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 14 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
