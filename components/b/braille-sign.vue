<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="t3g-tobka"/><path class="e75qrttrz"/><path class="qr13p2bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:braille-sign" /></template>
<style>
.e75qrttrz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.25v6m-3.25 0h6.5");
}

.qr13p2bua {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6.5h.01M7 9h.01M7 11.5h.01m2.99-5h.01M14 9h.01M17 6.5h.01m-.01 5h.01");
}

.t3g-tobka {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
