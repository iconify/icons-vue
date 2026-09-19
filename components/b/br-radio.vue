<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="d2bilk8zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:br-radio" /></template>
<style>
.d2bilk8zh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.739 16.731h2.89c2.69 0 4.871 2.186 4.871 4.882s-2.181 4.883-4.872 4.883m0 0l4.759 4.769M20.497 24a3.634 3.634 0 0 1 0 7.269H14.5V16.73h5.997a3.634 3.634 0 0 1 0 7.269Zm0 0H14.5");
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
