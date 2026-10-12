<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="l3f9vybbq"/><path class="nimtcozol"/><circle class="z6axribbu"/><circle class="uueil1pxw"/><path class="xcbkw0s1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:clips-scissors" /></template>
<style>
.l3f9vybbq {
  width: 18.5px;
  height: 7px;
  x: 2.75px;
  y: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.nimtcozol {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 7.5h.01m-.01 3h.01m13.49-3h.01m-.01 3h.01");
}

.uueil1pxw {
  cx: 17.5px;
  cy: 17.5px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcbkw0s1i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 15.5L16 3.25m-.5 12.25L8 3.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z6axribbu {
  cx: 6.5px;
  cy: 17.5px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
