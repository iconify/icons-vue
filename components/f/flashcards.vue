<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="u52qz0byu"/><path class="mwkw00q2n"/><path class="pfifjrafa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flashcards" /></template>
<style>
.mwkw00q2n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.75h12a2 2 0 0 1 2 2v12M7.6 11.9a2.5 2.5 0 1 1 3.4 2.35c-.6.25-1 .8-1 1.45v.55");
}

.pfifjrafa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 18.75h.01");
}

.u52qz0byu {
  width: 14.5px;
  height: 14.5px;
  x: 2.75px;
  y: 6.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
