<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o1enwbimn"/><rect class="j3s9ivbxi"/><path class="pa-o1levl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dkbtantogo" /></template>
<style>
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

.o1enwbimn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.7 38.4V27.2m0 0h4.7a2.8 2.8 0 1 1 0 5.6h-4.7m0 0h4.7a2.8 2.8 0 1 1 0 5.6h-4.7m-18.9 0V27.2h1.9a5.59 5.59 0 0 1 5.6 5.58v.02a5.59 5.59 0 0 1-5.58 5.6zm10.4-11.2v11.2m1.5-5.6l4.1-5.5m-4.1 5.5l4.1 5.6m-4.1-5.6h-1.5");
}

.pa-o1levl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.9 14.3h-.6v-2.1a3.8 3.8 0 1 0-7.6 0v2.1h-.6a1.37 1.37 0 0 0-1.4 1.4V23a1.37 1.37 0 0 0 1.4 1.4h8.8a1.37 1.37 0 0 0 1.4-1.4v-7.3a1.5 1.5 0 0 0-1.4-1.4m-8.2 0h7.5");
}

</style>
