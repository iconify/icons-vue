<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="sw4mtybyk"/><rect class="jmtduhbae"/><path class="j4qhdqbjb"/><path class="bwa-9sbrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:docking-station" /></template>
<style>
.bwa-9sbrs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 18.25h.01");
}

.j4qhdqbjb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 18.25h2m2 0h2");
}

.jmtduhbae {
  width: 18.5px;
  height: 6px;
  x: 2.75px;
  y: 15.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.sw4mtybyk {
  width: 6px;
  height: 10px;
  x: 9px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
