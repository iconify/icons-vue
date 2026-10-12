<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pzxdpzffj"/><rect class="ib0pmhqjl"/><path class="zxnlgy5hq"/><path class="po5lp0myl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:label-maker" /></template>
<style>
.ib0pmhqjl {
  width: 13.5px;
  height: 14.5px;
  x: 5.25px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.po5lp0myl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 16h.01M12 16h.01M15 16h.01M9 18.5h.01m2.99 0h.01m2.99 0h.01");
}

.pzxdpzffj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6.75v-3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zxnlgy5hq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 9.75h7.5v3h-7.5Z");
}

</style>
