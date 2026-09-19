<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vso237b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:granny-2" /></template>
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

.vso237b4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.117 22.142v-7.433h1.778c1.006 0 1.82.817 1.82 1.825s-.814 1.824-1.82 1.824h-1.778m1.778 0l1.778 3.782m7.185.001v-7.432l3.598 7.432v-7.432m1.772 7.432v-7.432l3.599 7.432v-7.432m5.37 0l-1.799 4.716l-1.799-4.716m1.799 7.432v-2.716m-14.908.254h-2.406m-.597 2.462l1.8-7.432l1.799 7.432m-10.685-5.632a1.8 1.8 0 0 0-1.799-1.8h0a1.8 1.8 0 0 0-1.8 1.8v3.834a1.8 1.8 0 0 0 1.8 1.799h0a1.8 1.8 0 0 0 1.8-1.8v-.984h-1.8m11.116 9.326a2.284 2.284 0 0 1 2.735-2.238c.957.184 1.72 1.011 1.816 1.981c.071.721-.157 1.433-.656 1.87c-.923.81-3.895 2.994-3.895 2.994h4.564");
}

</style>
