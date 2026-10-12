<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="wnqy6eson"/><path class="t417hkbst"/><path class="qtp_m8b9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kangaroo" /></template>
<style>
.qtp_m8b9k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 6.75h.01");
}

.t417hkbst {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 11L6.5 12.5v1");
}

.wnqy6eson {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.25c0-1 .5-1.75 1.5-2l2-.5l.75-1.25c.25-.5.75-.25.75.25V5.5c1.25.75 1.5 2 1.5 3V9c2.75.5 4.25 2.5 4.5 5l.25 2.25c.25 1 1 2 2.25 2.75l1.75 1c.25.5 0 1-.5 1l-2.75-.5c-1.5-.25-2.75-1-3.25-1.75V19c0 .5-.5 1-1.25 1h-3.5c-.5 0-.75-.5-.25-.75L10.25 18c-1.5-1.25-2.5-3-2.5-4.75V9L6 8.5c-1.25-.25-1.75-.75-1.75-1.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
