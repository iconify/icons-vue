<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="zelcsxs6c"/><path class="du9e61aam"/><circle class="optez1bab"/><path class="vxp1gibff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:action-camera" /></template>
<style>
.du9e61aam {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.75v-2.5h3.5v2.5");
}

.optez1bab {
  cx: 14.5px;
  cy: 13px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxp1gibff {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 10.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zelcsxs6c {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

</style>
