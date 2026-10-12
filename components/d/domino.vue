<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="a66apqljz"/><path class="frx9hsrjd"/><path class="m3fpj3xmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:domino" /></template>
<style>
.a66apqljz {
  width: 11px;
  height: 18.5px;
  x: 6.5px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.frx9hsrjd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12h7");
}

.m3fpj3xmp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 5.5h.01M12 7.4h.01m2.49 1.9h.01M9.5 15h.01m4.99 0h.01M9.5 18.25h.01m4.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
