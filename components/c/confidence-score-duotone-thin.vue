<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hyc57_bbg"/><path class="mcrp9i-9c"/><path class="gpcpf0b6m"/><path class="dp0hs2b_u"/><path class="vddehgbmg"/><path class="ghf6zpb7j"/><path class="x0qn9gsac"/><path class="g7qu0vb4t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confidence-score-duotone-thin" /></template>
<style>
.dp0hs2b_u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g7qu0vb4t {
  d: path("M21 14v4");
}

.ghf6zpb7j {
  d: path("M14 12v6");
}

.gpcpf0b6m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 8v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hyc57_bbg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m2 14 3 3 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcrp9i-9c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vddehgbmg {
  d: path("m2 14 3 3 5 -5");
}

.x0qn9gsac {
  d: path("M17.5 8v10");
}

</style>
