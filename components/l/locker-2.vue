<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h9t7uuebx"/><path class="zm6zq-i4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:locker-2" /></template>
<style>
.h9t7uuebx {
  cx: 9.962px;
  cy: 24px;
  r: 4.956px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zm6zq-i4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.918 24h13.536m-2.772 2.349V24m-6.605 2.5v13.542a3.46 3.46 0 0 0 3.458 3.458h17a3.46 3.46 0 0 0 3.459-3.458V7.958A3.46 3.46 0 0 0 39.535 4.5h-17a3.46 3.46 0 0 0-3.458 3.458V21.5m-.001-12.005h23.918m-23.918 29.01h23.918");
}

</style>
