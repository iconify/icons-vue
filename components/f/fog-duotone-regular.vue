<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="d483k8bnq"/><path class="tbe304aqf"/><path class="l0tg10jig"/><path class="xgrfb-bqu"/><path class="vzfmp7bra"/><path class="ys-dg812g"/><path class="wneoubc6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fog-duotone-regular" /></template>
<style>
.be306ynmy {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d483k8bnq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l0tg10jig {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 21h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tbe304aqf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
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

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
