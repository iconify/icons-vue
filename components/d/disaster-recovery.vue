<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="cbcus8y-t"/><path class="qlx4gxb8g"/><rect class="wf5ddcbyv"/><path class="c8_arzq0q"/><path class="bx2i3yfwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:disaster-recovery" /></template>
<style>
.bx2i3yfwl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.25 17.75a3.5 3.5 0 1 1-1.03-2.47m-1.5 0h1.5v-1.5");
}

.c8_arzq0q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 13.63h.01");
}

.cbcus8y-t {
  width: 13.5px;
  height: 5.75px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.qlx4gxb8g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 5.63h.01");
}

.wf5ddcbyv {
  width: 13.5px;
  height: 5.75px;
  x: 2.75px;
  y: 10.75px;
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
