<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z41hf4b9g"/><path class="i4ddl5bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ice-tray" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4ddl5bmk {
  d: path("M3.75 16.25h16.5m-8.25-5v10m1.57-17.9l2.16-.45q1.17-.25 1.42.92l.45 2.16q.25 1.17-.92 1.42l-2.16.45q-1.17.25-1.42-.92l-.45-2.16q-.25-1.17.92-1.42");
}

.z41hf4b9g {
  width: 16.5px;
  height: 10px;
  x: 3.75px;
  y: 11.25px;
  rx: 2px;
}

</style>
