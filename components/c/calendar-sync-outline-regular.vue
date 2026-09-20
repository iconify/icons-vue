<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jrpnc2pnl"/><path class="x50q_4bdr"/><path class="qaa4bo00g"/><path class="j6apg33fy"/><path class="txu63z8de"/><path class="tcrxzr6nz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:calendar-sync-outline-regular" /></template>
<style>
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

.tcrxzr6nz {
  d: path("M10.5 18H8a1 1 0 0 1 -1 -1v-2.5a1 1 0 0 1 1 -1h2.5");
}

.txu63z8de {
  d: path("M13.5 13.5H16a1 1 0 0 1 1 1V17a1 1 0 0 1 -1 1h-2.5");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
