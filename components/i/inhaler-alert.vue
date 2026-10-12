<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wmsphx-1a"/><path class="axlrqabvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inhaler-alert" /></template>
<style>
.axlrqabvj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.25 14.5h.01m.74 3h.01m-.76 3h.01");
}

.wmsphx-1a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 10.75h4a1 1 0 0 1 1 1v3.75h4.75a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5H12a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 6 19.5v-7.75a1 1 0 0 1 1-1m.5 0v-6.5A1.25 1.25 0 0 1 8.75 3h1A1.25 1.25 0 0 1 11 4.25v6.5Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
