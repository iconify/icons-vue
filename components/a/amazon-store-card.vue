<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="w6ulylosy"/><path class="s5-22g8zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-store-card" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s5-22g8zq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.462 20.349c1.482 2.161 6.542 6.329 12.715 8.229c5.885 1.81 10.133.784 12.397.056");
}

.w6ulylosy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.29 32.59l6.3-20.46a3.344 3.344 0 0 1 4.18-2.22l30.18 9.29m-9.463 7.597c1.395-.121 3.809-.109 4.225.901c.45 1.093-1.04 2.704-2.329 3.916");
}

</style>
