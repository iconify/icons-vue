<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b-zs71bsj"/><rect class="zf1t6xmvv"/><path class="cox0aibau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:horizon" /></template>
<style>
.b-zs71bsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.337 42.266l15.397.055M20.8 42.293v-6.276h6.304v6.287");
}

.cox0aibau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 26.924h37M9.755 13.864v-3.676h3.898m-.551 16.736c-3.908-4.917.614-9.437 3.57-9.428c1.289-7.22 15.045-10.31 16.68 2.287c2.937 1.662 3.704 4.547 1.952 7.141");
}

.zf1t6xmvv {
  width: 37px;
  height: 27.453px;
  x: 5.5px;
  y: 5.679px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.387px;
  ry: 2.387px;
}

</style>
