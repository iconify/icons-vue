<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ioq1zn9wa"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:indie" /></template>
<style>
.ioq1zn9wa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.002 29.349V18.651l5.443 10.698V18.651m15.947 5.568H38.5m0 5.13h-4.108v-10.26H38.5M21.946 29.35v-10.7h3.704c.96 0 1.74.78 1.74 1.74v7.22c0 .96-.78 1.74-1.74 1.74zM9.5 18.651v10.698m21.391-10.698v10.698");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
