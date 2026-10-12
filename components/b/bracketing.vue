<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pix837b7l"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bracketing" /></template>
<style>
.pix837b7l {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 3.75h-2.5a1 1 0 0 0-1 1v14.5a1 1 0 0 0 1 1h2.5m7.5-16.5h2.5a1 1 0 0 1 1 1v14.5a1 1 0 0 1-1 1h-2.5");
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
