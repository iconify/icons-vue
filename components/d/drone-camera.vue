<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m58075b4n"/><rect class="qh95m6b4i"/><path class="t8yioqebj"/><circle class="v257oxh1f"/><path class="ejow8ertj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drone-camera" /></template>
<style>
.ejow8ertj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17h.01");
}

.m58075b4n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5h5m8.5 0h5M8 8.75H5.25V4.5M16 8.75h2.75V4.5");
}

.qh95m6b4i {
  width: 8px;
  height: 5px;
  x: 8px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.t8yioqebj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11.75v2.75");
}

.v257oxh1f {
  cx: 12px;
  cy: 17px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
