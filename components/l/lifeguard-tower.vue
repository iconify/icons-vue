<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j44qbjbxe"/><rect class="refctzjtf"/><path class="nlobwibdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lifeguard-tower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j44qbjbxe {
  d: path("m4.88 7.59l6.49-4.18q.63-.41 1.26 0l6.49 4.18Q19.75 8 19 8H5q-.75 0-.12-.41");
}

.nlobwibdp {
  d: path("M6.75 8h10.5M8 13.5l-2.75 7.75M16 13.5l2.75 7.75");
}

.refctzjtf {
  width: 10.5px;
  height: 5.5px;
  x: 6.75px;
  y: 8px;
  rx: 0.75px;
}

</style>
