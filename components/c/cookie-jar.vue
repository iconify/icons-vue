<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="sov72xlyl"/><rect class="zb9g-0j7t"/><path class="hw8v2sz7z"/><path class="e_cac_uni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cookie-jar" /></template>
<style>
.e_cac_uni {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 12.75h.01M12.5 16h.01");
}

.hw8v2sz7z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.59 12.52a4.75 4.75 0 1 1-2.21-2.88a1.9 1.9 0 0 0 2.21 2.88");
}

.sov72xlyl {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zb9g-0j7t {
  width: 16.5px;
  height: 15px;
  x: 3.75px;
  y: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

</style>
