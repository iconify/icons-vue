<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="phu67w_rf"/><path class="l5f6efb9k"/><path class="vuvtqubwk"/><path class="l9c3qzbax"/><path class="zugrvnb7t"/><path class="t-oxscctn"/><path class="j08f9ezai"/><path class="dihddo_by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:horizon-duotone-bold" /></template>
<style>
.dihddo_by {
  d: path("M6 18h12");
}

.j08f9ezai {
  d: path("m12 13 4 -4 4 4");
}

.l5f6efb9k {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 13 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l9c3qzbax {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.phu67w_rf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 13h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t-oxscctn {
  d: path("m5 13 4 -4 4 4");
}

.vuvtqubwk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 13 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
