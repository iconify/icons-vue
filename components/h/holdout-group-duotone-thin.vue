<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j93aodlin"/><path class="f3oxrjbrz"/><path class="v7yx62j9c"/><path class="oor1gpbtp"/><path class="l2x-_sd5q"/><path class="xcjkf-bzr"/><path class="id5fryblw"/><path class="wa8tqsbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:holdout-group-duotone-thin" /></template>
<style>
.f3oxrjbrz {
  fill: currentColor;
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.id5fryblw {
  d: path("M15.5 4v16");
}

.j93aodlin {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l2x-_sd5q {
  d: path("M3 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.oor1gpbtp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v7yx62j9c {
  fill: currentColor;
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wa8tqsbro {
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xcjkf-bzr {
  d: path("M9 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
