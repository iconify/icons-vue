<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="ndmyj0ctx"/><path class="u5add9sjx"/><circle class="b6sj3-bad"/><path class="b4latebtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:access-granted" /></template>
<style>
.b4latebtc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.75 16.75l1.5 1.5l2.75-3");
}

.b6sj3-bad {
  cx: 16.75px;
  cy: 16.75px;
  r: 4.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ndmyj0ctx {
  width: 11px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.u5add9sjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.25 11.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
