<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ds-po1z3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kidzsearch" /></template>
<style>
.ds-po1z3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.594 30.639c1.04 1.354 2.346 1.859 4.16 1.859h2.513a4.233 4.233 0 0 0 4.233-4.233v-.018a4.233 4.233 0 0 0-4.233-4.233h-2.771a4.237 4.237 0 0 1-4.238-4.238a4.247 4.247 0 0 1 4.247-4.246h2.499c1.815 0 3.12.504 4.16 1.859M12.5 15.502v16.995m0-5.92l9.135-11.018m0 16.938L14.637 24");
}

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

</style>
