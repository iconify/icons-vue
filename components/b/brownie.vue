<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dl0xl9bdl"/><path class="h9qnlab5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brownie" /></template>
<style>
.dl0xl9bdl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 10.5L7 9l2.5 1L12 8.75l2.5 1L17 8.5l2.5 1.25v8.75a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2Z");
}

.h9qnlab5j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 14h.01m5.99-.75h.01M11.75 17h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
