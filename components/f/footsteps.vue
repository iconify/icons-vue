<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="qdbihc56r"/><path class="ep7dh_bss"/><path class="x_0w95b7u"/><path class="uck5v-b_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:footsteps" /></template>
<style>
.ep7dh_bss {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 9h.01M5 9.75h.01");
}

.qdbihc56r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 12c1.6 0 2.75 1.3 2.75 3.25c0 1.5-.75 2.25-.75 3.5c0 1.4-.8 2.25-2 2.25s-2.25-.9-2.25-2.25c0-1.25-.75-1.9-.75-3.5c0-1.95 1.4-3.25 3-3.25");
}

.uck5v-b_e {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 3.5h.01m3.49.75h.01");
}

.x_0w95b7u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.25 6.5c-1.6 0-2.75 1.3-2.75 3.25c0 1.5.75 2.25.75 3.5c0 1.4.8 2.25 2 2.25s2.25-.9 2.25-2.25c0-1.25.75-1.9.75-3.5c0-1.95-1.4-3.25-3-3.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
