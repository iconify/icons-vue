<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kddcd8xhg"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:braces" /></template>
<style>
.kddcd8xhg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 3.75H8a2 2 0 0 0-2 2V9.5A2.5 2.5 0 0 1 3.5 12A2.5 2.5 0 0 1 6 14.5v3.75a2 2 0 0 0 2 2h.75m6.5-16.5H16a2 2 0 0 1 2 2V9.5a2.5 2.5 0 0 0 2.5 2.5a2.5 2.5 0 0 0-2.5 2.5v3.75a2 2 0 0 1-2 2h-.75");
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
