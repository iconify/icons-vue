<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mz_p1fb6e"/><path class="nn4ux4lyn"/><path class="jond5s9ol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:goat" /></template>
<style>
.jond5s9ol {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 11.75h.01m2.99 0h.01");
}

.mz_p1fb6e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 8.5h7c0 3.75-.75 7-1.75 9.25L12 21.25l-1.75-3.5c-1-2.25-1.75-5.5-1.75-9.25");
}

.nn4ux4lyn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9.75h-3a.75.75 0 0 0-.6 1.2C5.75 12 7.05 12.5 8.75 12.5Zm7 0h3a.75.75 0 0 1 .6 1.2c-.85 1.05-2.15 1.55-3.85 1.55ZM10 8.5c-.5-3-2.5-5-5.75-5.25M14 8.5c.5-3 2.5-5 5.75-5.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
