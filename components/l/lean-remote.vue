<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="clwcuknez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lean-remote" /></template>
<style>
.clwcuknez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.311 13.452a13.95 13.95 0 0 1 4.697 10.507h0c-.002 7.545-5.825 13.66-13.008 13.66s-13.004-6.113-13.008-13.657a13.96 13.96 0 0 1 4.52-10.356M24 8.929v16.644");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
