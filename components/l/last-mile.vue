<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w0owrhbiz"/><rect class="mosqp9bnd"/><path class="yl3i9hxnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:last-mile" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mosqp9bnd {
  width: 6.5px;
  height: 5.75px;
  x: 8.75px;
  y: 13.25px;
  rx: 0.75px;
}

.w0owrhbiz {
  d: path("M3.75 10.4a1 1 0 0 1 .35-.76l7.25-6.2a1 1 0 0 1 1.3 0l7.25 6.2a1 1 0 0 1 .35.76v9.35a1.5 1.5 0 0 1-1.5 1.5H5.25a1.5 1.5 0 0 1-1.5-1.5Z");
}

.yl3i9hxnm {
  d: path("M12 13.25v2");
}

</style>
