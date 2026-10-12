<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="zz7891u5n"/><path class="g_a7evbzt"/><path class="jyqu8-btc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-kiss" /></template>
<style>
.g_a7evbzt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 11.25h.01m5.49 0h.01");
}

.jyqu8-btc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 14.25c1 0 1.5.4 1.5.9s-.5.85-1.5.85c1 0 1.5.4 1.5.9s-.5.85-1.5.85M19 6.8c-1.35-.99-2.25-1.8-2.25-2.79c0-.68.5-1.17 1.13-1.17c.5 0 .9.27 1.13.68c.23-.41.63-.68 1.13-.68c.63 0 1.13.5 1.13 1.17c0 .99-.9 1.8-2.25 2.79Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zz7891u5n {
  cx: 10.75px;
  cy: 13.25px;
  r: 8px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
