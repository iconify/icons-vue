<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="aex4p0z2m"/><path class="yd1dd2b-v"/><path class="p56aeiufb"/><path class="xgrfb-bqu"/><path class="vzfmp7bra"/><path class="ys-dg812g"/><path class="wneoubc6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fog-duotone-thin" /></template>
<style>
.aex4p0z2m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.earhjk-cy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p56aeiufb {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 21h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vzfmp7bra {
  d: path("M5 11h14");
}

.wneoubc6n {
  d: path("M7 21h10");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
