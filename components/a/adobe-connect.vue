<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="eti3crb1s"/><path class="p871z-gxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-connect" /></template>
<style>
.eti3crb1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 12h7.714v7.714H12zm16.286 0H36v7.714h-7.714zm0 16.286H36V36h-7.714zm-16.286 0h7.714V36H12z");
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

.p871z-gxj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36 19.714l-16.286 8.572L28.286 12M12 19.714l7.714 8.572v-8.572M28.286 36l-8.572-7.714h8.572");
}

</style>
