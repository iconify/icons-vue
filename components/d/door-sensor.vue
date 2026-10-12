<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ndmyj0ctx"/><path class="l7xf9eb2w"/><rect class="qczhm1bne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:door-sensor" /></template>
<style>
.l7xf9eb2w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.5 12h.01");
}

.ndmyj0ctx {
  width: 11px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.qczhm1bne {
  width: 3.25px;
  height: 6px;
  x: 18px;
  y: 6.75px;
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
