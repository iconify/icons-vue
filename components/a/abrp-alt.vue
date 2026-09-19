<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="r-ve6y3xv"/><path class="een_4xy5a"/><path class="xe02u6aye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:abrp-alt" /></template>
<style>
.een_4xy5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.227 37.332c-8.526 1.638-9.886-9.938-20.5-8.009");
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

.r-ve6y3xv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.15 42.5c2.38-7.84 9.18-14.31 12.35-21.58M16.81 5.5a14.7 14.7 0 0 0-2.38 8.05c0 10.62 10.87 18.58 14.02 28.95");
}

.xe02u6aye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.109 39.066c-9.023 2.944-14.913-6.308-21.382-3.672M35.7 10.6l-7.857.2l-2.557 11.49l3.055-.7l-1.682 7.696l7.766-9.58l-4.368.493z");
}

</style>
