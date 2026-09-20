<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f6q7r5bds"/><path class="krwm4ebpd"/><path class="z294x9ozg"/><path class="e3-4tuf3d"/><path class="awhoa5biy"/><path class="x02q_d2hh"/><path class="bbuvl1-kv"/><path class="hr8tx7nsp"/><path class="ew7y79byi"/><path class="huj3g_bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baby-shower-duotone-bold" /></template>
<style>
.awhoa5biy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m18 13 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bbuvl1-kv {
  d: path("M4 13h14");
}

.e3-4tuf3d {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 13h14");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.krwm4ebpd {
  fill: currentColor;
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.x02q_d2hh {
  d: path("M4 13a7 7 0 0 1 14 0");
}

.z294x9ozg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 13a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
