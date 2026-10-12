<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fwph8mbzq"/><path class="y_9og4gqt"/><path class="mabzxy7cw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-cowboy" /></template>
<style>
.fwph8mbzq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12.75a7.75 7.75 0 0 0 15.5 0Z");
}

.mabzxy7cw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 17.25c1.4.8 3.1.8 4.5 0M2.75 8c2.5 1.5 6 2.1 9.25 2.1s6.75-.6 9.25-2.1M7.75 9.6l.75-5.35c.15-.85 1.05-1.3 1.8-.85L12 4.5l1.7-1.1c.75-.45 1.65 0 1.8.85l.75 5.35");
}

.y_9og4gqt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 14.75h.01m5.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
