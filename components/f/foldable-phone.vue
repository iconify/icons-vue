<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="fi0i07b4o"/><path class="qfwi6wb1g"/><path class="g6asczbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:foldable-phone" /></template>
<style>
.fi0i07b4o {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.g6asczbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 7.5h.01");
}

.qfwi6wb1g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.25v15.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
