<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="v2y9ndosd"/><path class="wa8u43bsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hyena" /></template>
<style>
.v2y9ndosd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.25c0-.75.5-1.25 1.25-1.5L7 7.5l.25-2.25c.1-.6.8-.85 1.2-.4L10 6.75c3 0 6.5 2 9.25 5.5c.9 1.15 1.5 2.6 1.5 4V20h-2.5v-3.5h-5.5l-1 3.5h-2.5l.5-5C8 13 6.5 12.25 5.5 11.75H4.25c-.75 0-1.25-.65-1.25-1.5");
}

.wa8u43bsb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.25 10.25h.01m3.24 3h.01m-3.76.5h.01M7.5 9.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
