<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="xaz90clio"/><path class="i7k9zlcho"/><path class="m01tkpbrp"/><path class="k6nj2fbya"/><path class="rkhcgsbdl"/><path class="flq2w3bwj"/><path class="k5f0ncbhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cross-attention-duotone-bold" /></template>
<style>
.flq2w3bwj {
  d: path("m9.5 9.5 5 5");
}

.h7vr07ufd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i7k9zlcho {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 9.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k5f0ncbhf {
  d: path("m14.5 9.5 -5 5");
}

.k6nj2fbya {
  d: path("M3 5h18");
}

.m01tkpbrp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14.5 9.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xaz90clio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
