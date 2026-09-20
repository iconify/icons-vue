<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4fme0p6q"/><path class="r9jjpnb6g"/><path class="i9ez0hbmr"/><path class="evth9xjbs"/><path class="ng35sb6yg"/><path class="u4c9tcc0l"/><path class="t50oj1u1o"/><path class="eyettubom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-gauge-duotone-bold" /></template>
<style>
.c4fme0p6q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.evth9xjbs {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18.5 16H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eyettubom {
  d: path("M18.5 16H21");
}

.i9ez0hbmr {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.r9jjpnb6g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 16 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t50oj1u1o {
  d: path("M3 16h2.5");
}

.u4c9tcc0l {
  d: path("m12 16 5 -5");
}

</style>
