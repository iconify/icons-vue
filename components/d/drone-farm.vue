<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="r1xd_1h5j"/><path class="d4-q0kait"/><path class="pcxhgbbyh"/><path class="di_xzj1nc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drone-farm" /></template>
<style>
.d4-q0kait {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7.25H4.5m10.5 0h4.5m-16.75-3h3.5m11.5 0h3.5m-16.75 0v3m15-3v3");
}

.di_xzj1nc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h18.5M6 21.25v-2.5m0 0c-1.25 0-2-.75-2.25-2m2.25 2c1.25 0 2-.75 2.25-2m3.75 4.5v-2.5m0 0c-1.25 0-2-.75-2.25-2m2.25 2c1.25 0 2-.75 2.25-2m3.75 4.5v-2.5m0 0c-1.25 0-2-.75-2.25-2m2.25 2c1.25 0 2-.75 2.25-2");
}

.pcxhgbbyh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01m2.49.5h.01m2.49-.5h.01m-3.76 3h.01m2.49 0h.01");
}

.r1xd_1h5j {
  width: 6px;
  height: 3.5px;
  x: 9px;
  y: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
