<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z92okmbgh"/><path class="oakzecbvd"/><path class="jrpnc2pnl"/><path class="x50q_4bdr"/><path class="qaa4bo00g"/><path class="j6apg33fy"/><path class="eha2jo6cu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calendar-heart-duotone-thin" /></template>
<style>
.eha2jo6cu {
  d: path("M8.5 14a1.75 1.75 0 0 1 3.5 0 1.75 1.75 0 0 1 3.5 0L12 17.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6apg33fy {
  d: path("M16 2.5V5");
}

.jrpnc2pnl {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.oakzecbvd {
  fill: currentColor;
  d: path("M8.5 14a1.75 1.75 0 0 1 3.5 0 1.75 1.75 0 0 1 3.5 0L12 17.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qaa4bo00g {
  d: path("M8 2.5V5");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.z92okmbgh {
  fill: currentColor;
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
