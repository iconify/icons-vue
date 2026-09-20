<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fecwpdb_s"/><path class="lbllh8b8w"/><path class="qc-1i0btz"/><path class="ozi-k-boi"/><path class="n-7t0yb1r"/><path class="qw2d5tbco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:anomaly-band-duotone-regular" /></template>
<style>
.fecwpdb_s {
  fill: currentColor;
  d: path("M14 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lbllh8b8w {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 7h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.qc-1i0btz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qw2d5tbco {
  d: path("M14 18.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
