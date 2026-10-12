<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wkrmndk0j"/><rect class="w4_qaac_c"/><path class="mdse-fver"/><path class="qg5oveh_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:foil-roll" /></template>
<style>
.mdse-fver {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 11.75h.01");
}

.qg5oveh_m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.65 14.75h10.2q.4 0 .4.4v1.95q0 .4-.28.69l-.82.86q-.27.29-.63.1l-.67-.37q-.35-.19-.63.1l-.82.86q-.27.29-.63.1l-.67-.37q-.35-.19-.63.09l-.82.87q-.27.29-.63.1l-.67-.38q-.35-.19-.63.1l-.82.86q-.27.29-.63.1l-.67-.37q-.35-.19-.35-.59v-4.7q0-.4.4-.4");
}

.w4_qaac_c {
  width: 18.5px;
  height: 6px;
  x: 2.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.wkrmndk0j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 8.75l1.25-5h13l1.25 5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
