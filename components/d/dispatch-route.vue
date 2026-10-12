<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="nlse8_ejk"/><path class="z-gdo1blb"/><path class="v4ewq5b7w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dispatch-route" /></template>
<style>
.nlse8_ejk {
  width: 6.5px;
  height: 6.5px;
  x: 2.75px;
  y: 14.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.v4ewq5b7w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 6.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z-gdo1blb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 18h4.25a3 3 0 0 0 3-3v-1.75m0-10.5a3.75 3.75 0 0 1 3.75 3.75c0 3.58-3.75 6.5-3.75 6.5s-3.75-2.93-3.75-6.5a3.75 3.75 0 0 1 3.75-3.75");
}

</style>
