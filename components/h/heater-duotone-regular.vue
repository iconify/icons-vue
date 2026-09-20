<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="guj09_l3v"/><path class="x2cjm5bzr"/><path class="jlme50m5v"/><path class="jqd3s4bjf"/><path class="ri38s1oyl"/><path class="l20ha3bpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:heater-duotone-regular" /></template>
<style>
.guj09_l3v {
  fill: currentColor;
  d: path("M4 12a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jlme50m5v {
  d: path("M9 10v11");
}

.jqd3s4bjf {
  d: path("M15 10v11");
}

.l20ha3bpi {
  d: path("M16 2.5a2.5 2.5 0 0 1 0 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ri38s1oyl {
  d: path("M8 7.5a2.5 2.5 0 0 1 0 -5");
}

.x2cjm5bzr {
  d: path("M4 12a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
