<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jtdoh9bdf"/><circle class="j7ymcybsg"/><circle class="lyuiivbah"/><path class="jf-j82b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forkhub" /></template>
<style>
.j7ymcybsg {
  cx: 16.1px;
  cy: 9.08px;
  r: 4.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jf-j82b1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.1 34.34V13.66m0 19.01c0-5.4 5-8.67 11.22-8.67");
}

.jtdoh9bdf {
  cx: 16.1px;
  cy: 38.92px;
  r: 4.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lyuiivbah {
  cx: 31.9px;
  cy: 24px;
  r: 4.58px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
