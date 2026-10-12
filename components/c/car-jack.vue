<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ird2lib0e"/><rect class="pchrc21dm"/><path class="a0pd7gvtr"/><path class="fqfekabon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-jack" /></template>
<style>
.a0pd7gvtr {
  d: path("M12 5.25L6.5 12l5.5 6.75L17.5 12Z");
}

.fqfekabon {
  d: path("M4.75 12h13.5a2 2 0 0 1 2 2v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ird2lib0e {
  width: 16.5px;
  height: 2.5px;
  x: 3.75px;
  y: 18.75px;
  rx: 1px;
}

.pchrc21dm {
  width: 7.5px;
  height: 2.5px;
  x: 8.25px;
  y: 2.75px;
  rx: 1px;
}

</style>
