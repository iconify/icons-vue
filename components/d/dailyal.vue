<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jgnlfwb2i"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dailyal" /></template>
<style>
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

.jgnlfwb2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.037 29.442V18.554m0 6.396a2.744 2.744 0 0 0-2.766-2.721a2.744 2.744 0 0 0-2.771 2.717v1.775c0 1.501 1.239 2.721 2.77 2.721a2.744 2.744 0 0 0 2.767-2.72m8.73 2.72V22.23m0 4.492A2.744 2.744 0 0 1 24 29.442a2.744 2.744 0 0 1-2.77-2.717v-1.774c0-1.502 1.238-2.722 2.77-2.722c1.528 0 2.767 1.216 2.767 2.721m3.2-6.388v10.884H35.5");
}

</style>
