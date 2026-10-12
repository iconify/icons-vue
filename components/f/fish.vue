<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xpuy9ioeh"/><path class="fmt7gtbnv"/><path class="khtnmgbqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fish" /></template>
<style>
.fmt7gtbnv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 11h.01");
}

.khtnmgbqk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 9.25c.75 1.75.75 3.75 0 5.5");
}

.xpuy9ioeh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12c2-3.5 5-5.25 8-5.25S20.25 9.5 21.25 12c-1 2.5-2.75 5.25-5.75 5.25s-6-1.75-8-5.25m-1 0L3.75 8.75a.6.6 0 0 0-1 .4v5.7a.6.6 0 0 0 1 .4Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
