<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="qepibxl-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hueber" /></template>
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

.qepibxl-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.165 18.421v8.483m5.62-8.483v8.483m-5.62-4.348h5.62m1.488-1.139v3.5c0 1.166.955 2.12 2.121 2.12a2.126 2.126 0 0 0 2.121-2.12v-3.5m0 3.605v2.121m18.199-3.55c0-1.166.954-2.12 2.12-2.12m-2.12-.001v5.726m-12.859-1.203c-.318.636-1.06 1.06-1.803 1.06a2.127 2.127 0 0 1-2.12-2.12v-1.38c0-1.166.954-2.12 2.12-2.12s2.12.954 2.12 2.12v.743h-4.24m15.08 1.77c-.318.636-1.06 1.06-1.803 1.06a2.127 2.127 0 0 1-2.12-2.12v-1.38c0-1.166.954-2.12 2.12-2.12s2.12.954 2.12 2.12v.743h-4.24m-5.577-.977c0-1.167.954-2.121 2.12-2.121s2.122.954 2.122 2.12v1.38c0 1.166-.955 2.12-2.121 2.12a2.127 2.127 0 0 1-2.12-2.12m-.001 2.226v-8.483M5.5 30.37h37");
}

</style>
