<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gcm12vbdr"/><path class="v3mivhbeb"/><path class="pcl5pkbcw"/><path class="votyijv0m"/><path class="tlwdv3zao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:baking-duotone-thin" /></template>
<style>
.gcm12vbdr {
  fill: currentColor;
  d: path("M5 9a3 3 0 0 1 3 -3h8a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcl5pkbcw {
  d: path("M2 9h3");
}

.tlwdv3zao {
  d: path("M4 20c3 -3 13 -3 16 0");
}

.v3mivhbeb {
  d: path("M5 9a3 3 0 0 1 3 -3h8a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3");
}

.votyijv0m {
  d: path("M19 9h3");
}

</style>
