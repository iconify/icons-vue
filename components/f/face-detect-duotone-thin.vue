<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ag-dyktzc"/><path class="l8kkrt56f"/><path class="fzxau2bqc"/><path class="mp8d-bcnh"/><path class="dyzdq66vg"/><path class="a75-p3jrr"/><path class="gllvw82zq"/><path class="i4lcqvyfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:face-detect-duotone-thin" /></template>
<style>
.a75-p3jrr {
  d: path("M13.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ag-dyktzc {
  fill: currentColor;
  d: path("M5 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.dyzdq66vg {
  d: path("M8.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.fzxau2bqc {
  fill: currentColor;
  d: path("M13.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gllvw82zq {
  d: path("M3 7V3h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4lcqvyfj {
  d: path("M21 17v4h-4");
}

.l8kkrt56f {
  fill: currentColor;
  d: path("M8.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mp8d-bcnh {
  d: path("M5 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

</style>
