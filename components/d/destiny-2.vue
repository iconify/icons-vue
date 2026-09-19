<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="y73l8_gch"/><path class="lxn0znkwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:destiny-2" /></template>
<style>
.lxn0znkwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.897 10.209a25.7 25.7 0 0 1-6.546-2.494c-.193-.136-.873-.495-.873-.495a5.622 5.622 0 0 0-5.55 9.73c5.428 4.096 10.44 11.384 10.44 18.723a5.632 5.632 0 0 0 11.264 0c0-7.339 5.012-14.627 10.44-18.722a5.62 5.62 0 0 0-5.55-9.731s-.68.359-.873.494a25.7 25.7 0 0 1-6.546 2.494");
}

.y73l8_gch {
  width: 8.192px;
  height: 15.019px;
  x: 19.904px;
  y: 8.764px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.096px;
}

</style>
