<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrnaf3n0k"/><circle class="p6zc61wkl"/><path class="tb6yno8ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:find-family" /></template>
<style>
.lrnaf3n0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 16.97a11.05 11.05 0 0 0-11.042 11.042c0 4.314 2.726 8.254 5.41 11.098a36 36 0 0 0 5.362 4.703L24 44l.27-.187a36 36 0 0 0 5.362-4.703c2.684-2.872 5.41-6.804 5.41-11.098A11.05 11.05 0 0 0 24 16.97");
}

.p6zc61wkl {
  cx: 24px;
  cy: 28.293px;
  r: 2.761px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tb6yno8ys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.927 12.253a12.15 12.15 0 0 1 12.146 0M13.51 6.81a20.98 20.98 0 0 1 20.98 0");
}

</style>
