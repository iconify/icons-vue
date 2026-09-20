<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xnwdi1b1d"/><path class="wjuupqz4l"/><path class="h68oqyb7w"/><path class="z48szeaan"/><path class="lt8hrxcjt"/><path class="km2_vvbqp"/><path class="c7dgfu7wx"/><path class="ek759fs3g"/><path class="d3kpl_b4o"/><path class="od769abab"/><path class="pj7ux4r4p"/><path class="o8od38cnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-stage-duotone-bold" /></template>
<style>
.c7dgfu7wx {
  d: path("M2 4h20");
}

.d3kpl_b4o {
  d: path("M5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ek759fs3g {
  d: path("M7 4v3");
}

.h68oqyb7w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 4h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km2_vvbqp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lt8hrxcjt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o8od38cnm {
  d: path("M4 18h16");
}

.od769abab {
  d: path("M17 4v3");
}

.pj7ux4r4p {
  d: path("M15 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wjuupqz4l {
  fill: currentColor;
  d: path("M15 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xnwdi1b1d {
  fill: currentColor;
  d: path("M5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z48szeaan {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
