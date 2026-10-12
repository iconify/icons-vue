<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hufrlzpcu"/><path class="pxdjhw_3y"/><path class="v_h_ylb4t"/><path class="vzolxrb_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:browser-agent" /></template>
<style>
.hufrlzpcu {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.pxdjhw_3y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.25h18.5");
}

.v_h_ylb4t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 6h.01");
}

.vzolxrb_o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.5q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
