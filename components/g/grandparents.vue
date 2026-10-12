<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ewjw_yj_k"/><circle class="lsli-sbem"/><path class="d3boadcyy"/><circle class="dfgi7qjss"/><path class="qv2snbhqr"/><path class="q9y___orc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grandparents" /></template>
<style>
.d3boadcyy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25v-2.5a3.75 3.75 0 0 1 7.5 0v2.5Z");
}

.dfgi7qjss {
  cx: 17.5px;
  cy: 9.5px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ewjw_yj_k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.07 7.45a2 2 0 1 1 2.86 0a2.5 2.5 0 0 0-2.86 0");
}

.lsli-sbem {
  cx: 6.5px;
  cy: 9.5px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q9y___orc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.4 9.5h2.2m-4.85 11.75v-2.5a3.75 3.75 0 0 1 7.5 0v2.5Z");
}

.qv2snbhqr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.4 9.5h.01m2.19 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
