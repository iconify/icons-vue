<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="zxknbac4f"/><path class="nfu5cdcdo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coupon" /></template>
<style>
.nfu5cdcdo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 9.75h.01m4.49 4.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zxknbac4f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75a2 2 0 0 1 2-2h14.5a2 2 0 0 1 2 2V9.5a2.5 2.5 0 0 0 0 5v1.75a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2V14.5a2.5 2.5 0 0 0 0-5Zm7 6.5l4.5-4.5");
}

</style>
