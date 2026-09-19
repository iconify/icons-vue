<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="uhu93mb0u"/><circle class="eho5yumgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hikconnect" /></template>
<style>
.eho5yumgp {
  cx: 24px;
  cy: 24px;
  r: 2.25px;
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

.uhu93mb0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.934 25.254c-.692 6.591-6.597 11.373-13.188 10.68a12 12 0 0 1-10.68-10.68m0-2.508c.692-6.591 6.597-11.373 13.188-10.68a12 12 0 0 1 10.68 10.68");
}

</style>
