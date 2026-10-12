<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m0446obdq"/><path class="o8yd5p_pg"/><path class="gxf0_bc0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flute" /></template>
<style>
.gxf0_bc0u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.17 15.37l2.47 2.47");
}

.m0446obdq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.47 17.06L17.06 4.47q1.06-1.06 2.12 0l.35.35q1.06 1.06 0 2.12L6.94 19.53q-1.06 1.06-2.12 0l-.35-.35q-1.06-1.06 0-2.12");
}

.o8yd5p_pg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.94 13.06h.01m2.11-2.12h.01m2.11-2.12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
