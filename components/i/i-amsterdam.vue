<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ulkf_sb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:i-amsterdam" /></template>
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

.ulkf_sb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.193 18.75v11m16.533-4.86a2.75 2.75 0 0 1 2.75-2.75h0a2.75 2.75 0 0 1 2.75 2.75v4.538m-5.5-7.287v7.287m5.5-4.538a2.75 2.75 0 0 1 2.75-2.75h0a2.75 2.75 0 0 1 2.75 2.75v4.538m-14.017-2.632a2.75 2.75 0 0 1-2.75 2.75h0a2.75 2.75 0 0 1-2.75-2.75v-1.787a2.75 2.75 0 0 1 2.75-2.75h0a2.75 2.75 0 0 1 2.75 2.75m0 4.537v-7.287");
}

</style>
