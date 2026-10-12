<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="x8tipsb3g"/><rect class="i4auq8vnx"/><path class="ekmihcb8x"/><path class="bjth-8b6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clipboard-list" /></template>
<style>
.bjth-8b6g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 11h3.75m-3.75 4h3.75");
}

.ekmihcb8x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 11h.01m-.01 4h.01");
}

.i4auq8vnx {
  width: 6.5px;
  height: 3.5px;
  x: 8.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.x8tipsb3g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 4.25h-1.5a2.5 2.5 0 0 0-2.5 2.5v12a2.5 2.5 0 0 0 2.5 2.5h9.5a2.5 2.5 0 0 0 2.5-2.5v-12a2.5 2.5 0 0 0-2.5-2.5h-1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
