<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f6q7r5bds"/><path class="krwm4ebpd"/><path class="shpomxm_s"/><path class="jd4gh4buj"/><path class="kohtq6bwj"/><path class="x02q_d2hh"/><path class="bbuvl1-kv"/><path class="hr8tx7nsp"/><path class="ew7y79byi"/><path class="huj3g_bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baby-shower-duotone-regular" /></template>
<style>
.bbuvl1-kv {
  d: path("M4 13h14");
}

.ew7y79byi {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.f6q7r5bds {
  fill: currentColor;
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hr8tx7nsp {
  d: path("m18 13 3 -3");
}

.huj3g_bus {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jd4gh4buj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kohtq6bwj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m18 13 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.krwm4ebpd {
  fill: currentColor;
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.shpomxm_s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 13a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x02q_d2hh {
  d: path("M4 13a7 7 0 0 1 14 0");
}

</style>
