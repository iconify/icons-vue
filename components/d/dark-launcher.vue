<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s-x6-9yxy"/><circle class="tvwua2ucc"/><circle class="xieiogb1j"/><circle class="m10v5nbga"/><circle class="qgbkv6han"/><circle class="dmuq-t1vf"/><circle class="jlpbzdb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dark-launcher" /></template>
<style>
.dmuq-t1vf {
  cx: 35.926px;
  cy: 26.639px;
  r: 0.75px;
  fill: currentColor;
}

.jlpbzdb3f {
  cx: 37.882px;
  cy: 34.483px;
  r: 0.75px;
  fill: currentColor;
}

.m10v5nbga {
  cx: 34.665px;
  cy: 8.113px;
  r: 0.75px;
  fill: currentColor;
}

.qgbkv6han {
  cx: 25.858px;
  cy: 3.701px;
  r: 0.75px;
  fill: currentColor;
}

.s-x6-9yxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 37.728c-11.874 0-21.5-9.626-21.5-21.5c0-5.016 1.732-9.62 4.61-13.277C9.843 4.978 2.5 13.631 2.5 24c0 11.874 9.626 21.5 21.5 21.5c6.858 0 12.953-3.223 16.89-8.224a21.6 21.6 0 0 1-4.39.452M25.108 14.159V8.607m-2.776 2.776h5.551m12.785 12.365v-2.356m-1.177 1.178h2.355M28.22 30.561v-2.355m-1.178 1.177h2.355");
}

.tvwua2ucc {
  cx: 22.363px;
  cy: 22.139px;
  r: 0.75px;
  fill: currentColor;
}

.xieiogb1j {
  cx: 31.763px;
  cy: 20.814px;
  r: 0.75px;
  fill: currentColor;
}

</style>
