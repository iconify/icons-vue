<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="goh99yf5t"/><path class="txi96rt4a"/><circle class="l-zq-1mft"/><circle class="ejqc9bb9x"/><circle class="a870vdb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:classroom" /></template>
<style>
.a870vdb4y {
  cx: 18.75px;
  cy: 18.25px;
  r: 2px;
}

.ejqc9bb9x {
  cx: 12px;
  cy: 18.25px;
  r: 2px;
}

.goh99yf5t {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-zq-1mft {
  cx: 5.25px;
  cy: 18.25px;
  r: 2px;
}

.txi96rt4a {
  d: path("M6.5 7.75h7");
}

</style>
