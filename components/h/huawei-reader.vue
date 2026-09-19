<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="l-8r14b-h"/><rect class="i8_iucb3y"/><path class="rzflegbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-reader" /></template>
<style>
.i8_iucb3y {
  width: 16.137px;
  height: 13.75px;
  x: 26.363px;
  y: 17.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.992px;
}

.l-8r14b-h {
  width: 16.137px;
  height: 13.75px;
  x: 5.5px;
  y: 17.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.992px;
}

.rzflegbpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.637 23.045h4.727m4.916-1.075v4.536M10.107 21.97v4.536");
}

</style>
