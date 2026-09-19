<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="d9m5lacjb"/><path class="zta7oy6hj"/><path class="ygmweqbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:debix" /></template>
<style>
.d9m5lacjb {
  width: 29.981px;
  height: 19.711px;
  x: 4.5px;
  y: 19.765px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.ygmweqbak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.005 13.018h3.987v3.987h-3.987zM8.988 32.762h13.553M8.988 35.747h6.821");
}

.zta7oy6hj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.988 24.253h3.987v3.987H8.988zm25.491 3.997H40.5c1.65 0 3-1.35 3-3V11.523c0-1.65-1.35-3-3-3H16.52c-1.65 0-3 1.35-3 3v8.243");
}

</style>
