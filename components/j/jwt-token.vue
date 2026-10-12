<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="qsm9g2nxy"/><path class="x1byofbyi"/><path class="e8bv_pb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jwt-token" /></template>
<style>
.e8bv_pb1o {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.5h.01M8 17h.01");
}

.qsm9g2nxy {
  width: 16px;
  height: 17px;
  x: 4px;
  y: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.x1byofbyi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-3 5h1.75m6.5 0H17M11.25 17H17");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
