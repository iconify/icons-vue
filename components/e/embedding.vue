<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="vvlo9_k1g"/><path class="le4tdx-dj"/><rect class="q6jtl7b2i"/><path class="gyaiatuwu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:embedding" /></template>
<style>
.gyaiatuwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 7h.01m-.01 5h.01m-.01 5h.01");
}

.le4tdx-dj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12h2.5m-1.5-1.5l1.5 1.5l-1.5 1.5");
}

.q6jtl7b2i {
  width: 6px;
  height: 18.5px;
  x: 15.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.vvlo9_k1g {
  width: 5.5px;
  height: 5.5px;
  x: 2.75px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.75px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
