<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fwzy69olr"/><path class="mnw_-bdju"/><path class="nhw4qt96j"/><path class="c9c7gubje"/><path class="rd_tpe20s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dependency-arrow-duotone-regular" /></template>
<style>
.c9c7gubje {
  d: path("M6.5 7v5h11v5");
}

.fwzy69olr {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mnw_-bdju {
  fill: currentColor;
  d: path("M13 19a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nhw4qt96j {
  d: path("M2 5a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rd_tpe20s {
  d: path("M13 19a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2");
}

</style>
