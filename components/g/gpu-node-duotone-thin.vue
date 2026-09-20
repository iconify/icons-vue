<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hlgur3d9q"/><path class="sf079yb1a"/><path class="gs7wgfben"/><path class="nd4pi4b2u"/><path class="x7whap_kh"/><path class="dyr8x0ydm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gpu-node-duotone-thin" /></template>
<style>
.dyr8x0ydm {
  d: path("M13.5 3.5v3");
}

.gs7wgfben {
  d: path("M2 14h6");
}

.hlgur3d9q {
  fill: currentColor;
  d: path("M8 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nd4pi4b2u {
  d: path("M16 14h6");
}

.sf079yb1a {
  d: path("M8 14a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.x7whap_kh {
  d: path("M10.5 3.5v3");
}

</style>
