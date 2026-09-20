<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="id48gub1a"/><path class="mbt4yzbhr"/><path class="kfyfc0bjf"/><path class="x2s-wnp4x"/><path class="k15q4tbdt"/><path class="z9ittvbis"/><path class="bnhdslb0j"/><path class="kyf663bil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dusk-duotone-regular" /></template>
<style>
.bnhdslb0j {
  d: path("M19 8v6");
}

.id48gub1a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 19a6 6 0 0 1 12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k15q4tbdt {
  d: path("M6 19a6 6 0 0 1 12 0");
}

.kfyfc0bjf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kyf663bil {
  d: path("M16.5 11.5 19 14l2.5 -2.5");
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x2s-wnp4x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16.5 11.5 19 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
