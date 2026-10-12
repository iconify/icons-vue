<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qysga69jn"/><path class="jdinfrbxs"/><path class="ow73bhs5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:key-fob" /></template>
<style>
.jdinfrbxs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.96 7.25a3 3 0 1 0-3.46 3.46");
}

.ow73bhs5r {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 11.75h.01M13.5 16h.01");
}

.qysga69jn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 7.25h7.25a4 4 0 0 1 4 4v5.25a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4V8a.75.75 0 0 1 .75-.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
