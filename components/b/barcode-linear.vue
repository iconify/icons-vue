<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gndbq0bkl"/><path class="dpokkjq8r"/><path class="mazoy0feo"/><path class="c9rugwb_d"/><path class="niumi_b1d"/><rect class="j34g79pdg"/><rect class="rcdscmf_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-linear" /></template>
<style>
.c9rugwb_d {
  stroke-linecap: round;
  d: path("M22 18.978L22 4.97803");
}

.dpokkjq8r {
  stroke-linecap: round;
  d: path("M5.53906 18.9785L5.53906 4.97852");
}

.gndbq0bkl {
  stroke-linecap: round;
  d: path("M12.3164 18.9785L12.3164 4.97852");
}

.j34g79pdg {
  width: 0.968px;
  height: 14.043px;
  x: 8.444px;
  y: 4.957px;
  rx: 0.484px;
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mazoy0feo {
  stroke-linecap: round;
  d: path("M15.2217 18.9785L15.2217 4.97852");
}

.niumi_b1d {
  stroke-linecap: round;
  d: path("M2.63379 18.9785L2.63379 4.97852");
}

.rcdscmf_t {
  width: 0.968px;
  height: 14.043px;
  x: 18.127px;
  y: 4.935px;
  rx: 0.484px;
}

</style>
