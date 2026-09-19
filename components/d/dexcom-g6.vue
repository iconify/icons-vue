<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cfq9kh__b"/><circle class="hzwa77b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dexcom-g6" /></template>
<style>
.cfq9kh__b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5C13.249 4.5 4.5 13.249 4.5 24S13.249 43.5 24 43.5S43.5 34.751 43.5 24V4.5z");
}

.hzwa77b_s {
  cx: 24px;
  cy: 24px;
  r: 13.703px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
