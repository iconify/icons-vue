<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ve-t3_box"/><rect class="vfps7ja1y"/><rect class="cu7lfubfx"/><rect class="b9kfnqb3r"/><path class="izangtb6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:assembly-line" /></template>
<style>
.b9kfnqb3r {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 16.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.cu7lfubfx {
  width: 5px;
  height: 4.5px;
  x: 14.25px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.izangtb6s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 18.75h.01m11.99 0h.01");
}

.ve-t3_box {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 2.75v3m-2 0h4");
}

.vfps7ja1y {
  width: 5px;
  height: 4.5px;
  x: 4.75px;
  y: 8.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
