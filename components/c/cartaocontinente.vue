<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="f7147tb6g"/><circle class="hmizyiyip"/><circle class="zj59rjbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cartaocontinente" /></template>
<style>
.f7147tb6g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.202 26.816a3.428 3.428 0 0 1-6.405-1.701v-2.23a3.43 3.43 0 0 1 3.429-3.427c1.271 0 2.381.692 2.973 1.72");
}

.hmizyiyip {
  cx: 24px;
  cy: 24px;
  r: 8.622px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.zj59rjbnw {
  cx: 27.44px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
