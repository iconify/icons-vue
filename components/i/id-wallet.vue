<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="l3e21ac-g"/><circle class="qa4oqibtz"/><path class="qpbgzrbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:id-wallet" /></template>
<style>
.l3e21ac-g {
  width: 36.65px;
  height: 26.043px;
  x: 5.675px;
  y: 10.979px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.qa4oqibtz {
  cx: 14.838px;
  cy: 21.487px;
  r: 3.563px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qpbgzrbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.328 31.095h9.783a.92.92 0 0 0 .7-1.52a7.172 7.172 0 0 0-11.183 0a.92.92 0 0 0 .7 1.52M28.709 20.85h6.999m-6.999 6.872h6.999m-6.999-3.436h9.671");
}

</style>
