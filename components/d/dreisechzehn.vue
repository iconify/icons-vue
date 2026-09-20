<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yygqwrbpr"/><circle class="sx_4imbbr"/><path class="wxb7z5d4v"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dreisechzehn" /></template>
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

.sx_4imbbr {
  cx: 30.919px;
  cy: 11.152px;
  r: 0.75px;
  fill: currentColor;
}

.wxb7z5d4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.919 13.434v4.936m-2.107-.94a1.863 1.863 0 0 1-3.481-.923v-1.21a1.863 1.863 0 1 1 3.725 0v.605h-3.725m-3.194-.606c0-1.028.834-1.862 1.863-1.862m-1.863 0v4.936m-1.982-3.074a1.863 1.863 0 1 0-3.725 0v1.211a1.863 1.863 0 1 0 3.725 0m0 1.863v-7.451");
}

.yygqwrbpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.08 37.5v-3.073a1.863 1.863 0 1 0-3.725 0m-.001 3.073v-4.936m-5.67-2.515V37.5m0-3.073a1.863 1.863 0 1 1 3.725 0V37.5m-5.901-.94a1.863 1.863 0 0 1-3.481-.923v-1.21a1.863 1.863 0 1 1 3.725 0v.605h-3.725m-5.107-2.468h3.726L13.92 37.5h3.726m12.463-17.016v7.45m.001-3.073a1.863 1.863 0 1 1 3.725 0v3.073m-5.623-.938a1.862 1.862 0 0 1-3.48-.924v-1.21a1.863 1.863 0 0 1 3.478-.929m-5.585 3.062a1.863 1.863 0 0 1-3.481-.923v-1.21a1.863 1.863 0 1 1 3.725 0v.604h-3.726m-4.86 2.052c.34.286.707.417 1.532.417h.418c.68 0 1.231-.553 1.231-1.234c0-.682-.551-1.234-1.231-1.234h-.836a1.234 1.234 0 0 1 0-2.468h.418c.824 0 1.192.13 1.532.416");
}

</style>
