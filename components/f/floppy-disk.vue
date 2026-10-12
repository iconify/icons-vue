<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gstmt8cgv"/><rect class="f42y3lb7b"/><path class="ds5-r6van"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:floppy-disk" /></template>
<style>
.ds5-r6van {
  d: path("M14.5 6.5v2.25m-7.75 5.5h10.5m-10.5 3h10.5");
}

.f42y3lb7b {
  width: 8.5px;
  height: 5.25px;
  x: 8.75px;
  y: 5px;
  rx: 1px;
}

.gstmt8cgv {
  d: path("M2.75 7.4a2 2 0 0 1 .6-1.4L6 3.35a2 2 0 0 1 1.4-.6h11.35a2.5 2.5 0 0 1 2.5 2.5v13.5a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
