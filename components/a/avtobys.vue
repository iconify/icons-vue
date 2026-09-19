<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kiq8yrbri"/><circle class="ytp-b9a3p"/><path class="doay0qbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:avtobys" /></template>
<style>
.doay0qbqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.937 14.979a19.56 19.56 0 0 1 10.126 0M16.397 5.5a29.4 29.4 0 0 1 15.206 0");
}

.kiq8yrbri {
  cx: 24px;
  cy: 33.875px;
  r: 0.75px;
  fill: currentColor;
}

.ytp-b9a3p {
  cx: 24px;
  cy: 33.875px;
  r: 9.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
