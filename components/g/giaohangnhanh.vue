<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="qhn357a1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:giaohangnhanh" /></template>
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

.qhn357a1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.963 5.57v14.47l-.002-.001l-5.92-4.911v.006l-5.995 4.898l-.009.009V5.57m12.09 30.665v-9.619l6.373 9.619v-9.619m-15.811-.001v9.62m6.373-9.62v9.62m-6.373-4.828h6.373m-9.189-1.605a3.187 3.187 0 0 0-3.187-3.186h0a3.187 3.187 0 0 0-3.186 3.186v3.247a3.187 3.187 0 0 0 3.186 3.186h0a3.187 3.187 0 0 0 3.187-3.186h-3.187");
}

</style>
