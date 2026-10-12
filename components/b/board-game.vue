<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f7r42znre"/><path class="qt2xr1blz"/><circle class="kf_2z4bao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:board-game" /></template>
<style>
.f7r42znre {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kf_2z4bao {
  cx: 17px;
  cy: 17.5px;
  r: 1.5px;
}

.qt2xr1blz {
  d: path("M6.5 6.5h9.25a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 15.75 12h-7.5a1.75 1.75 0 0 0-1.75 1.75v2a1.75 1.75 0 0 0 1.75 1.75H13");
}

</style>
