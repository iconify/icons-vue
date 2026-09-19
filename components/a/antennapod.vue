<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="y1dyi-2ff"/><path class="x48kjlb6p"/><path class="abf_5pb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:antennapod" /></template>
<style>
.abf_5pb8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.584 30.307c3.595-1.43 6.139-4.94 6.139-9.04c0-5.371-4.352-9.723-9.723-9.723s-9.723 4.352-9.723 9.723c0 4.1 2.544 7.61 6.139 9.04");
}

.x48kjlb6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.643 24.686L15.591 42.5m9.765-17.814L32.409 42.5m-2.607-6.57c5.834-2.312 9.965-8.01 9.965-14.663C39.767 12.564 32.703 5.5 24 5.5S8.233 12.564 8.233 21.267c0 6.654 4.131 12.35 9.965 14.663");
}

.y1dyi-2ff {
  cx: 24px;
  cy: 21.267px;
  r: 3.679px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
