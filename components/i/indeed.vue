<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="km49dimkq"/><ellipse class="qfdg9mrxe"/><path class="rac6dzfyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:indeed" /></template>
<style>
.km49dimkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.758 27.267V40.53c0 3.958 6.964 3.96 6.964 0V27.267a7.72 7.72 0 0 1-6.964 0");
}

.qfdg9mrxe {
  cx: 26.468px;
  cy: 16.146px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.17px;
  ry: 4.139px;
}

.rac6dzfyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.518 22.771c2.33-9.728 11.661-25.061 26.964-14.96");
}

</style>
