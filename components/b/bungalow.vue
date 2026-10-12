<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="nhokpxb5u"/><rect class="o6c9z3d4e"/><path class="nrm_r1bfd"/><path class="ywkpp0bhy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bungalow" /></template>
<style>
.nhokpxb5u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.56 10.16l7.63-5.57q.81-.59 1.62 0l7.63 5.57q.81.59-.19.59H3.75q-1 0-.19-.59");
}

.nrm_r1bfd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-4.5h3v4.5");
}

.o6c9z3d4e {
  width: 14.5px;
  height: 8px;
  x: 4.75px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ywkpp0bhy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16.5h.01m8.99 0h.01");
}

</style>
