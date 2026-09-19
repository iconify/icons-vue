<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gf8pe0nhy"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apex-icon-pack" /></template>
<style>
.gf8pe0nhy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.539 19.5l5.3 8m0-8l-5.3 8m-13.107 0v-8h2.619c1.48 0 2.68 1.203 2.68 2.687s-1.2 2.686-2.68 2.686h-2.62m7.222-1.373h2.608m1.392 4h-4v-8h4m-14.07 5.35h-3.544m-.878 2.65l2.65-8l2.65 8");
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
