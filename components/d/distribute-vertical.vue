<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhclxacbk"/><rect class="p7fqmbcmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:distribute-vertical" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7fqmbcmq {
  width: 12.5px;
  height: 6px;
  x: 5.75px;
  y: 9px;
  rx: 1.5px;
}

.zhclxacbk {
  d: path("M2.75 3.75h18.5m-18.5 16.5h18.5");
}

</style>
