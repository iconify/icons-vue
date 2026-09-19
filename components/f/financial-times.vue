<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="eutcjaczc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:financial-times" /></template>
<style>
.eutcjaczc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.624 31.346V16.653M13.6 24h4.686M13.6 31.346V16.653h7.21v1.172m-2.524 5.003v2.343m-3.515 6.175h-2.343m18.368 0h-2.343m5.948-13.521v-1.172h-9.553v1.172m-12.42-1.172H13.6");
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
