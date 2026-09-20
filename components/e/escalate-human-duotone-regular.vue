<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oibtokbpn"/><path class="snyoiwbte"/><path class="ffeh-4b3n"/><path class="pdk95vb_h"/><path class="q6kjd1w_g"/><path class="u70k4y_qc"/><path class="fevuzkbbx"/><path class="bfcwd7bcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:escalate-human-duotone-regular" /></template>
<style>
.bfcwd7bcm {
  d: path("M13 13a4 4 0 0 1 8 0");
}

.fevuzkbbx {
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ffeh-4b3n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 15 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oibtokbpn {
  fill: currentColor;
  d: path("M15 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pdk95vb_h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q6kjd1w_g {
  d: path("M7.5 13.83a3.5 3.5 0 1 1 -2.96 0");
}

.snyoiwbte {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 13.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u70k4y_qc {
  d: path("m9 15 5 -5");
}

</style>
