<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m0b8wlabx"/><circle class="uycxedbit"/><path class="qyrds1bwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:call-record" /></template>
<style>
.m0b8wlabx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.6 3.25h2.6a1 1 0 0 1 .95.68l1.1 3.3A1 1 0 0 1 10 8.25l-1.6 1.6a12.5 12.5 0 0 0 5.75 5.75l1.6-1.6a1 1 0 0 1 1.02-.25l3.3 1.1a1 1 0 0 1 .68.95v2.6a2.35 2.35 0 0 1-2.35 2.35c-8.3 0-15.15-6.85-15.15-15.15A2.35 2.35 0 0 1 5.6 3.25");
}

.qyrds1bwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 6.25h.01");
}

.uycxedbit {
  cx: 17.75px;
  cy: 6.25px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
