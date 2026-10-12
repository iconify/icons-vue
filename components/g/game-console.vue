<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="b3kdyb5si"/><path class="u46jdubse"/><path class="csx_8sbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:game-console" /></template>
<style>
.b3kdyb5si {
  width: 18.5px;
  height: 6.5px;
  x: 2.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.csx_8sbvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 12h.01M18 12h.01");
}

.u46jdubse {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12h2.5m-1.25-1.25v2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
