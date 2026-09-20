<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kagwbabxk"/><path class="d5b4fcc2f"/><path class="l8xl8ub_k"/><path class="ygu6pgbdd"/><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="kyf663bil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dusk-duotone-bold" /></template>
<style>
.bnhdslb0j {
  d: path("M19 8v6");
}

.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k15q4tbdt {
  d: path("M6 19a6 6 0 0 1 12 0");
}

.kagwbabxk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 19a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kyf663bil {
  d: path("M16.5 11.5 19 14l2.5 -2.5");
}

.l8xl8ub_k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ygu6pgbdd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 11.5 19 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
