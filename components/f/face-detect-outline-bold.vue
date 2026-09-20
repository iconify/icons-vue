<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mp8d-bcnh"/><path class="dyzdq66vg"/><path class="a75-p3jrr"/><path class="gllvw82zq"/><path class="i4lcqvyfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:face-detect-outline-bold" /></template>
<style>
.a75-p3jrr {
  d: path("M13.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dyzdq66vg {
  d: path("M8.5 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gllvw82zq {
  d: path("M3 7V3h4");
}

.i4lcqvyfj {
  d: path("M21 17v4h-4");
}

.mp8d-bcnh {
  d: path("M5 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
