<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="tclgz3b1m"/><path class="ypc0kvmlx"/><path class="bw67xsb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:del2" /></template>
<style>
.bw67xsb5s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.208 22.599c-1.069 1.031-2.382 1.454-4.585 1.454m4.995-4.349c0 1.801-2.256 2.668-4.46 2.668");
}

.tclgz3b1m {
  width: 39px;
  height: 19.5px;
  x: 4.5px;
  y: 14.713px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.318px;
  ry: 5.318px;
}

.ypc0kvmlx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.49 20.837l-2.552 7.01c-.24.66.1 1.193.759 1.193h3.934m-11.029-4.101h3.699m-.065 4.101h-3.934c-.659 0-.999-.534-.759-1.193l2.117-5.817c.24-.658.969-1.193 1.628-1.193h3.934M8.38 29.04l2.987-8.203h2.87c1.983 0 3.005 1.607 2.283 3.59l-.373 1.025c-.721 1.982-2.913 3.589-4.895 3.589zm30.9 0h-4.286l.883-2.425c.163-.447.656-.809 1.103-.809h2.668c.447 0 .94-.362 1.103-.808l.589-1.618c.162-.446-.068-.808-.515-.808h-3.477m-9.288-3.365c.716-.526 1.964-.696 3.57-.696c2.202 0 3.988.534 3.988 1.193s-1.786 1.193-3.989 1.193l-1.006 3.156");
}

</style>
