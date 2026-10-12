<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="w4t3tcsnr"/><path class="to8m3ibcr"/><path class="qopss0bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:attack-surface" /></template>
<style>
.qopss0bjp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 3l3.5 3.5m0-2.75V6.5H3.75M21 3l-3.5 3.5m0-2.75V6.5h2.75M21 21l-3.5-3.5m0 2.75V17.5h2.75M3 21l3.5-3.5m0 2.75V17.5H3.75");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.w4t3tcsnr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.37 13.08l-1.24 2.17q-.63 1.08-1.88 1.08h-2.5q-1.25 0-1.88-1.08l-1.24-2.17Q7 12 7.63 10.92l1.24-2.17q.63-1.08 1.88-1.08h2.5q1.25 0 1.88 1.08l1.24 2.17q.63 1.08 0 2.16");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
