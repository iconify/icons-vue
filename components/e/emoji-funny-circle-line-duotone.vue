<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><circle class="jty_abcpu"/><path class="m-_j7-iyd"/><path class="tr1xg7b_k"/><path class="t6qg_cbvk"/><ellipse transform="rotate(-15 8.714 11.328)" class="l5tkhob0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:emoji-funny-circle-line-duotone" /></template>
<style>
.jty_abcpu {
  cx: 12px;
  cy: 12px;
  r: 10px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l5tkhob0v {
  cx: 8.714px;
  cy: 11.328px;
  rx: 0.5px;
  ry: 1px;
}

.m-_j7-iyd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.9126 15.9331C10.1709 16.2485 11.5985 16.2487 13.0351 15.8638C14.4717 15.4788 15.7079 14.7649 16.64 13.8626");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.t6qg_cbvk {
  d: path("M14.9923 9.64461C15.1353 10.1781 15.0349 10.6685 14.7682 10.7399C14.5014 10.8114 14.1693 10.4369 14.0264 9.90343C13.8835 9.36996 13.9838 8.87956 14.2505 8.80809C14.5173 8.73662 14.8494 9.11114 14.9923 9.64461Z");
}

.tr1xg7b_k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 16L13.478 16.9738C13.8393 17.71 14.7249 18.0194 15.4661 17.6685C16.2223 17.3106 16.5394 16.4031 16.1708 15.652L15.7115 14.7164");
}

</style>
