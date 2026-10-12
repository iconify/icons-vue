<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m_aic536w"/><path class="rrnp7cvhy"/><path class="msv_vkbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cat-smile" /></template>
<style>
.m_aic536w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13a8 8 0 0 0 16 0c0-1.75-.55-3.35-1.5-4.65l.25-4.1a1 1 0 0 0-1.6-.85L14 5.8a8 8 0 0 0-2-.55a8 8 0 0 0-2 .25L6.85 3.1a1 1 0 0 0-1.6.85l.25 4.1A7.9 7.9 0 0 0 4 13");
}

.msv_vkbbn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 16c.75.75 1.75.75 2.5 0c.75.75 1.75.75 2.5 0m-9.75-1.5l2.25.25m12.25-.25l-2.25.25");
}

.rrnp7cvhy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12h.01M15 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
