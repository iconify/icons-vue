<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zcp8fb90b"/><path class="h438ckbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:light-refraction" /></template>
<style>
.h438ckbje {
  d: path("M12 3v4.5m-7.5-3L12 12m0 0l2.25 6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zcp8fb90b {
  width: 18.5px;
  height: 9.25px;
  x: 2.75px;
  y: 12px;
  rx: 2.5px;
}

</style>
