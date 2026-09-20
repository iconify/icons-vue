<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vmveteb9f"/><path class="yd1dd2b-v"/><path class="uu4ikdboz"/><path class="sbqfxybpc"/><path class="xm60vxbgs"/><path class="ys-dg812g"/><path class="q1cfkyb_k"/><path class="hhn28yosy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:armchair-duotone-thin" /></template>
<style>
.hhn28yosy {
  d: path("M21 20v-8h-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q1cfkyb_k {
  d: path("M3 20v-8h4");
}

.sbqfxybpc {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 20v-8h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uu4ikdboz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20v-8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vmveteb9f {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 16V5h10v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xm60vxbgs {
  d: path("M7 16V5h10v11");
}

.yd1dd2b-v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
