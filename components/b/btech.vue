<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sc0fkobcn"/><circle class="s5nzj833e"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:btech" /></template>
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

.s5nzj833e {
  cx: 16.049px;
  cy: 27.59px;
  r: 0.75px;
  fill: currentColor;
}

.sc0fkobcn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.585 24.019c1.012 0 1.84.828 1.84 1.84s-.828 1.839-1.84 1.839H9.55V20.34h3.035c1.012 0 1.84.828 1.84 1.84s-.828 1.839-1.84 1.839m0 0H9.55m6.384-3.679h4.782m-2.391 7.358V20.34m4.044 3.679h2.391m1.287 3.679h-3.678V20.34h3.678m6.005 4.74a2.473 2.473 0 0 1-2.483 2.483h0c-1.38 0-2.484-1.104-2.484-2.392v-2.483c0-1.38 1.104-2.483 2.484-2.391h0a2.375 2.375 0 0 1 2.39 2.39h0m1.716-2.347v7.358m4.875-7.358v7.358m-4.875-3.771h4.875");
}

</style>
