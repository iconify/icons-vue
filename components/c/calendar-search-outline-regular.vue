<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jrpnc2pnl"/><path class="x50q_4bdr"/><path class="qaa4bo00g"/><path class="j6apg33fy"/><path class="zq866cmlw"/><path class="ec9py2bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calendar-search-outline-regular" /></template>
<style>
.ec9py2bye {
  d: path("m13.5 17 2.5 2.5");
}

.j6apg33fy {
  d: path("M16 2.5V5");
}

.jrpnc2pnl {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qaa4bo00g {
  d: path("M8 2.5V5");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

.zq866cmlw {
  d: path("M8.5 15a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
