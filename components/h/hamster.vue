<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="dw8g9qvgx"/><path class="qh8-e9n5t"/><path class="ap4rgkbzl"/><circle class="td69qzbgx"/><circle class="c-nzzb3th"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hamster" /></template>
<style>
.ap4rgkbzl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 11.75h1.5l-.75.75Zm.75.75v1m0 0c-.5.5-1.25.5-1.75.25M12 13.5c.5.5 1.25.5 1.75.25");
}

.c-nzzb3th {
  cx: 18px;
  cy: 14.5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dw8g9qvgx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5.5C7.25 4.5 8 4 8.75 4s1.25.5 1.5 1c.6-.15 1.15-.25 1.75-.25s1.15.1 1.75.25c.25-.5.75-1 1.5-1s1.5.5 1.75 1.5c2 1.5 3.25 4 3.25 7.25c0 4.75-3.5 8-8.25 8s-8.25-3.25-8.25-8C3.75 9.5 5 7 7 5.5");
}

.qh8-e9n5t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 9.75h.01m5.49 0h.01");
}

.td69qzbgx {
  cx: 6px;
  cy: 14.5px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
