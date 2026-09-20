<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e92t5ym8w"/><path class="f3kd6nx_d"/><path class="tbc9lglre"/><path class="dd2oi04rr"/><path class="giopbjb9g"/><path class="h_alycbda"/><path class="lb5uptbbe"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grass-duotone-regular" /></template>
<style>
.dd2oi04rr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e92t5ym8w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 19v-7l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f3kd6nx_d {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 19v-9l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.giopbjb9g {
  d: path("M5 19v-7l3 -3");
}

.h_alycbda {
  d: path("M10 19v-9l3 -3");
}

.lb5uptbbe {
  d: path("M16 19v-7l3 -3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.tbc9lglre {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 19v-7l3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
