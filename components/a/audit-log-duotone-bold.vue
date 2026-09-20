<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxow7abeb"/><path class="n0mccvbla"/><path class="abnm6smsv"/><path class="d2gpzsh-s"/><path class="qpr4gub3m"/><path class="v_xc_lbja"/><path class="ktnnerbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audit-log-duotone-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.d2gpzsh-s {
  d: path("M9 6v12");
}

.ktnnerbwt {
  d: path("M14 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n0mccvbla {
  fill: currentColor;
  d: path("M14 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qpr4gub3m {
  d: path("M11 9h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v_xc_lbja {
  d: path("M11 13h5");
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
