<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="rd4ffbunp"/><path class="h-z2g8xys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-sleep-mask" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.h-z2g8xys {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 12h4.5a2.25 2.25 0 0 1 2.25 2.25v1.5A2.25 2.25 0 0 1 14.25 18h-4.5a2.25 2.25 0 0 1-2.25-2.25v-1.5A2.25 2.25 0 0 1 9.75 12M7.5 13.25L3.3 11.5m13.2 1.75l4.2-1.75M9.75 15h4.5");
}

.rd4ffbunp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 8.75h.01m5.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
