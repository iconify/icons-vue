<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ke3lfbn7f"/><path class="khqqtqb0r"/><circle class="p6ts7bqqv"/><path class="c5t1d0bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aircare" /></template>
<style>
.c5t1d0bjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.069 25.878v7.086");
}

.ke3lfbn7f {
  cx: 24.069px;
  cy: 31.163px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9.927px;
  ry: 9.603px;
}

.khqqtqb0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.787 33.1h3.697c4.408 0 7.963-3.578 7.963-7.962a7.91 7.91 0 0 0-6.849-7.868a11.94 11.94 0 0 0-11.754-9.811a11.85 11.85 0 0 0-9.456 4.692a7.4 7.4 0 0 0-2.63-.474a7.687 7.687 0 0 0-7.702 7.702c0 .166 0 .355.023.521a6.852 6.852 0 0 0 2.512 13.224h4.764");
}

.p6ts7bqqv {
  cx: 24.069px;
  cy: 35.933px;
  r: 0.825px;
  fill: currentColor;
}

</style>
