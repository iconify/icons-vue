<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iv4_ub72l"/><path class="fj6gmgbtw"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:active-learning" /></template>
<style>
.fj6gmgbtw {
  d: path("M8.5 8.25a2.5 2.5 0 1 1 2.5 2.5V12m0 2.75h.01m9.74 3.75A2.75 2.75 0 1 1 18 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.iv4_ub72l {
  d: path("M7 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C3.5 6.25 6.75 3 11 3c4 0 7 2.75 7 6.75l1.5 3.5q.04.082.064.162");
}

</style>
