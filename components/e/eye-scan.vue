<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ufb5nlbai"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-scan" /></template>
<style>
.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ufb5nlbai {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8V6A2.25 2.25 0 0 1 6 3.75h2m8 0h2A2.25 2.25 0 0 1 20.25 6v2m0 8v2A2.25 2.25 0 0 1 18 20.25h-2m-8 0H6A2.25 2.25 0 0 1 3.75 18v-2m3-4c1.2-2.3 3-3.5 5.25-3.5s4.05 1.2 5.25 3.5c-1.2 2.3-3 3.5-5.25 3.5S7.95 14.3 6.75 12");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
