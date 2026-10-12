<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cvfl0cbaq"/><rect class="y9i2r-11z"/><path class="w5yxhp1xq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loan-check" /></template>
<style>
.cvfl0cbaq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25v7.5m3-6.5h2.5l2.1-1.1a2 2 0 0 1 .95-.25h2.45a1.5 1.5 0 0 1 0 3H11.5m-5.75 4.35h6.6a3 3 0 0 0 1.85-.65l5.6-4.4a1.5 1.5 0 0 0-1.85-2.35l-3.2 2.5");
}

.w5yxhp1xq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.75 6.38h.01");
}

.y9i2r-11z {
  width: 12px;
  height: 7.25px;
  x: 7.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
