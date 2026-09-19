<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="zku0nfbpl"/><path class="msbak4bhg"/><circle class="d6yqucc7v"/><circle class="uvowpq9fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dumb-ways-2" /></template>
<style>
.d6yqucc7v {
  cx: 18.594px;
  cy: 21.982px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.msbak4bhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.506 33.308v2.581a1.9 1.9 0 0 1-.934 1.64a1.85 1.85 0 0 1-1.868 0a1.9 1.9 0 0 1-.935-1.64l-.044-2.28m4.178-14.206c.708 1.044 1.12 2.62 1.12 4.285h0c0 3.038-1.344 5.5-3 5.5s-3-2.462-3-5.5c0-1.666.411-3.242 1.12-4.286m15.715.001c.708 1.044 1.12 2.62 1.12 4.285h0c0 3.038-1.344 5.5-3 5.5s-3-2.462-3-5.5h0c0-1.666.411-3.242 1.12-4.286");
}

.uvowpq9fg {
  cx: 30.55px;
  cy: 21.982px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zku0nfbpl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.403h37m-37-3.999h37M5.5 9.5h37M12.811 34.051c5.595-1.141 16.784-1.141 22.378 0");
}

</style>
