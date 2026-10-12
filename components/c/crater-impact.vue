<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jqu2-obpk"/><circle class="z88h98p6c"/><path class="ymi-zn1vi"/><path class="r2xb_gbqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crater-impact" /></template>
<style>
.jqu2-obpk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17h3.5c1.5 0 2 3.5 5.75 3.5s4.25-3.5 5.75-3.5h3.5");
}

.r2xb_gbqe {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.75 7.75h.01M12 4h.01m8.24 3.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ymi-zn1vi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 12.75l-2-2m6.75.5v-3m4.75 4.5l2-2");
}

.z88h98p6c {
  cx: 12px;
  cy: 15.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
