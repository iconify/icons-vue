<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w95bfobed"/><path class="tbmul1b-b"/><path class="e3b1-abws"/><path class="d1v960b6t"/><path class="yoxtsbceg"/><path class="nrqy16b7j"/><path class="em798y7rn"/><path class="pvfbz5b4i"/><path class="wy-zn0bse"/><path class="e9z836b7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:blizzard-duotone-thin" /></template>
<style>
.d1v960b6t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 3v6m-3 0 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e3b1-abws {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e9z836b7m {
  d: path("M18.5 15v6m-3 0 6 -6");
}

.em798y7rn {
  d: path("M6 12h14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrqy16b7j {
  d: path("M3 6h11");
}

.pvfbz5b4i {
  d: path("M3 18h11");
}

.tbmul1b-b {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w95bfobed {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wy-zn0bse {
  d: path("M18.5 3v6m-3 0 6 -6");
}

.yoxtsbceg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 15v6m-3 0 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
