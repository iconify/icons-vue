<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="o2-t0ac6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:economic-times" /></template>
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

.o2-t0ac6r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.025 32.114V15.886M14.641 24h5.253m2.798-8.114v1.517m0 13.194v1.517h-8.05V15.885h18.717v1.517m-13.465 5.081v3.034m9.648 6.597h-3.034m-11.867 0h-1.517m1.517-16.228h-1.517");
}

</style>
