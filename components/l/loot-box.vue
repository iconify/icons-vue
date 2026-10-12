<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="c_k3usb_h"/><rect class="sxk5pwb_d"/><path class="pgieaqchn"/><path class="isxmsmb2n"/><path class="sjh-zdctz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loot-box" /></template>
<style>
.c_k3usb_h {
  width: 18.5px;
  height: 3px;
  x: 2.75px;
  y: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.isxmsmb2n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19h.01");
}

.pgieaqchn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 14.5a1.5 1.5 0 1 1 2.1 1.37c-.4.18-.6.5-.6.93v.2");
}

.sjh-zdctz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V5M6.75 3.5l1 1.75m9.5-1.75l-1 1.75");
}

.sxk5pwb_d {
  width: 16px;
  height: 10.5px;
  x: 4px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
