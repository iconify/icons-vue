<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="zd0xlsb3c"/><path class="ml23jbcmh"/><path class="sze-r7bpy"/><path class="yw3eho_ht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hotel-building" /></template>
<style>
.ml23jbcmh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.25h5");
}

.sze-r7bpy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01m-6.01 4h.01m5.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yw3eho_ht {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-3h3v3");
}

.zd0xlsb3c {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

</style>
