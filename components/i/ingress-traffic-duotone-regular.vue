<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kp5q9696o"/><path class="ua6hpxbwj"/><path class="gmcwnnbyg"/><path class="p4a4wbc0p"/><path class="yvotc3bin"/><path class="m1k1s7nte"/><path class="mi_m6achy"/><path class="l_9_psbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ingress-traffic-duotone-regular" /></template>
<style>
.gmcwnnbyg {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kp5q9696o {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 3H3v18h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l_9_psbce {
  d: path("M21 6v12");
}

.m1k1s7nte {
  d: path("M10 12h10");
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4a4wbc0p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ua6hpxbwj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yvotc3bin {
  d: path("M8 3H3v18h5");
}

</style>
