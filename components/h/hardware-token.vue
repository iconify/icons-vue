<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d-ypa6b4i"/><path class="h8mhrib-l"/><rect class="heliymbif"/><path class="rzhow-3io"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hardware-token" /></template>
<style>
.d-ypa6b4i {
  width: 14.75px;
  height: 10.5px;
  x: 6.5px;
  y: 6.75px;
  rx: 3.5px;
}

.h8mhrib-l {
  d: path("M6.5 9.44a2.75 2.75 0 1 0 0 5.12");
}

.heliymbif {
  width: 9.5px;
  height: 5.5px;
  x: 9.25px;
  y: 9.25px;
  rx: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rzhow-3io {
  d: path("M11.25 12h1.25m2.75 0h1.25");
}

</style>
