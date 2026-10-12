<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="b2u8wh5yy"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hexagon-vertical" /></template>
<style>
.b2u8wh5yy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.5 13.73l-2.75 4.77q-1 1.73-3 1.73h-5.5q-2 0-3-1.73L3.5 13.73q-1-1.73 0-3.46L6.25 5.5q1-1.73 3-1.73h5.5q2 0 3 1.73l2.75 4.77q1 1.73 0 3.46");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
