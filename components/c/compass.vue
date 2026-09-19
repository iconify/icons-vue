<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="klvlxwbvc"/><circle class="wtdkvu9ae"/><path class="tthskmbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:compass" /></template>
<style>
.klvlxwbvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5A21.5 21.5 0 1 1 45.5 24A21.51 21.51 0 0 1 24 45.5m12.45-34.08l-12.3 8.96m12.3-8.96l-8.96 12.31");
}

.tthskmbvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.54 36.34l12.3-8.96m-12.3 8.96l8.96-12.3");
}

.wtdkvu9ae {
  cx: 24px;
  cy: 23.88px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
