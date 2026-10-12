<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="sr8ztfbjh"/><path class="tis8h6dcx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lost-luggage" /></template>
<style>
.sr8ztfbjh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.25v-1.5a1.5 1.5 0 0 1 1.5-1.5h1a1.5 1.5 0 0 1 1.5 1.5v1.5m-.75 12h-6.5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v1.5m-10-3.5v12m8-4.5a2.5 2.5 0 1 1 3.5 2.3c-.6.25-1 .7-1 1.2");
}

.tis8h6dcx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 20.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
