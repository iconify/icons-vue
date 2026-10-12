<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qaqcvgffg"/><path class="b3hzthn_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desk-phone" /></template>
<style>
.b3hzthn_j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 16.75h.01m3.49 0h.01m3.49 0h.01");
}

.qaqcvgffg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8.25V6.5c0-2 3.75-3.75 8.5-3.75s8.5 1.75 8.5 3.75v1.75a1 1 0 0 1-1 1H17a1 1 0 0 1-1-1V7c-1.2-.4-2.6-.6-4-.6s-2.8.2-4 .6v1.25a1 1 0 0 1-1 1H4.5a1 1 0 0 1-1-1m2.75 4h11.5q1.5 0 1.75 1.48l1 6.04q.25 1.48-1.25 1.48H4.75q-1.5 0-1.25-1.48l1-6.04q.25-1.48 1.75-1.48");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
