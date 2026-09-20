<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="naa67qbfw"/><path class="fgef0hcge"/><path class="i7k9zlcho"/><path class="m01tkpbrp"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="flq2w3bwj"/><path class="k5f0ncbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:feature-cross-duotone-bold" /></template>
<style>
.fgef0hcge {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.flq2w3bwj {
  d: path("m9.5 9.5 5 5");
}

.i7k9zlcho {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 9.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k5f0ncbhf {
  d: path("m14.5 9.5 -5 5");
}

.m01tkpbrp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14.5 9.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.naa67qbfw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3rq50btb {
  d: path("M19 4v16");
}

</style>
