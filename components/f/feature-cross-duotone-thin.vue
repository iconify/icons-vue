<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrmo-yb4e"/><path class="leef4tbvz"/><path class="tlaolnbzt"/><path class="vwmqidksx"/><path class="ppivcbbzp"/><path class="t3rq50btb"/><path class="flq2w3bwj"/><path class="k5f0ncbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:feature-cross-duotone-thin" /></template>
<style>
.flq2w3bwj {
  d: path("m9.5 9.5 5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5f0ncbhf {
  d: path("m14.5 9.5 -5 5");
}

.leef4tbvz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrmo-yb4e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ppivcbbzp {
  d: path("M5 4v16");
}

.t3rq50btb {
  d: path("M19 4v16");
}

.tlaolnbzt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 9.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vwmqidksx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14.5 9.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
