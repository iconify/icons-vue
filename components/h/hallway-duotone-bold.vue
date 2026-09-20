<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kdc5y_bms"/><path class="qfclk5djd"/><path class="guoi_acnp"/><path class="j8v_p1wrt"/><path class="oviqrkboq"/><path class="maf2tbbex"/><path class="oqfv9rb9x"/><path class="g-g6w6buq"/><path class="me7c_bbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hallway-duotone-bold" /></template>
<style>
.g-g6w6buq {
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.guoi_acnp {
  fill: currentColor;
  d: path("M7 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j8v_p1wrt {
  fill: currentColor;
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kdc5y_bms {
  fill: currentColor;
  d: path("M3 4h6v14H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.maf2tbbex {
  d: path("M15 4h6v14h-6Z");
}

.me7c_bbry {
  d: path("M15 11a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.oqfv9rb9x {
  d: path("M2 21h20");
}

.oviqrkboq {
  d: path("M3 4h6v14H3Z");
}

.qfclk5djd {
  fill: currentColor;
  d: path("M15 4h6v14h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
