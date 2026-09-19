<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ym24w5bim"/><circle class="jfu55pbog"/><path class="l1-_y7byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lavseeker" /></template>
<style>
.jfu55pbog {
  cx: 34.992px;
  cy: 12.279px;
  r: 5.83px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l1-_y7byj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 41.566H27.483l7.509-21.155zm-37-21.155h15.017l-7.509 21.155z");
}

.ym24w5bim {
  cx: 13.008px;
  cy: 12.264px;
  r: 5.83px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
