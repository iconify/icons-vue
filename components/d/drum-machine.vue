<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="o0xk3dbag"/><path class="mhm7ccc0x"/><path class="fdtrm7b0s"/><path class="b5pebvmua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drum-machine" /></template>
<style>
.b5pebvmua {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.25 14.75h1m2.5 0h1m2.5 0h1m2.5 0h1");
}

.fdtrm7b0s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 9.25h3.5");
}

.mhm7ccc0x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 9.25h.01m3.49 0h.01");
}

.o0xk3dbag {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
