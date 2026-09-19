<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="hch7o7t6p"/><path class="y2re3xb7o"/><path class="roi0e5bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bomber" /></template>
<style>
.hch7o7t6p {
  cx: 12.396px;
  cy: 11.265px;
  r: 4.667px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.roi0e5bol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.064 11.265c5.485 0 7.22-5.302 12.268-5.302c2.182 0 3.339 1.42 3.339 3.392c0 1.735-1.381 2.715-1.607 3.466");
}

.y2re3xb7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.051 18.209l-1.17-4.57l-5.784-1.682s-2.087 1.96-3.52 3.284c-6.865.858-12.18 6.703-12.18 13.801c0 7.689 6.232 13.921 13.92 13.921S40.24 36.73 40.24 29.042c0-4.38-2.026-8.281-5.188-10.833");
}

</style>
