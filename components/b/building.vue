<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="f8hk9kbgp"/><path class="bvqlz6eem"/><path class="wyegadcbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:building" /></template>
<style>
.bvqlz6eem {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 6.75h.01m5.99 0h.01M9 10.25h.01m5.99 0h.01M9 13.75h.01m5.99 0h.01");
}

.f8hk9kbgp {
  width: 13.5px;
  height: 18.5px;
  x: 5.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.wyegadcbh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 21.25v-3a1.75 1.75 0 0 1 3.5 0v3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
