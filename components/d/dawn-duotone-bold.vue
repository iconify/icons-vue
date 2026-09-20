<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kagwbabxk"/><path class="d5b4fcc2f"/><path class="l8xl8ub_k"/><path class="jm6olrbyo"/><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="vl804rbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dawn-duotone-bold" /></template>
<style>
.bnhdslb0j {
  d: path("M19 8v6");
}

.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jm6olrbyo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16.5 10.5 19 8l2.5 2.5");
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

.vl804rbny {
  d: path("M16.5 10.5 19 8l2.5 2.5");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
