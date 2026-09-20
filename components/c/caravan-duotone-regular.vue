<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jtbwiuhml"/><path class="wio383bia"/><path class="ullkw1r7p"/><path class="bxwb8qsga"/><path class="mep_pif7d"/><path class="q84iiacic"/><path class="a-w-mldxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:caravan-duotone-regular" /></template>
<style>
.a-w-mldxi {
  d: path("M19 10h3");
}

.bxwb8qsga {
  d: path("M3 15V5h16v10Z");
}

.jtbwiuhml {
  fill: currentColor;
  d: path("M3 15V5h16v10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mep_pif7d {
  d: path("M6 8h5v4H6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q84iiacic {
  d: path("M6 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ullkw1r7p {
  fill: currentColor;
  d: path("M6 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wio383bia {
  fill: currentColor;
  d: path("M6 8h5v4H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
