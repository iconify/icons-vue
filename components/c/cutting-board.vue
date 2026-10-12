<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="thuciqbpu"/><path class="urn9fgb8u"/><path class="bbktlbcro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cutting-board" /></template>
<style>
.bbktlbcro {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10h7m-7 3h7m-7 3h4.5");
}

.thuciqbpu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 6.25h9a2.5 2.5 0 0 1 2.5 2.5v1.5h2a2.5 2.5 0 0 1 2.5 2.5v.5a2.5 2.5 0 0 1-2.5 2.5h-2v1.5a2.5 2.5 0 0 1-2.5 2.5h-9a2.5 2.5 0 0 1-2.5-2.5v-8.5a2.5 2.5 0 0 1 2.5-2.5");
}

.urn9fgb8u {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 13h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
