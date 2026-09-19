<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="eyyfor--j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:2d" /></template>
<style>
.eyyfor--j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.794 31V17h3.15a6.125 6.125 0 0 1 6.125 6.125v1.75A6.125 6.125 0 0 1 28.944 31zm-12.863-9.362a4.642 4.642 0 0 1 5.558-4.55c1.945.374 3.498 2.056 3.692 4.027c.144 1.466-.32 2.913-1.333 3.802C18.972 26.563 12.931 31 12.931 31h9.275");
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
