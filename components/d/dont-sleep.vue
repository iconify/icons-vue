<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="erd8-3b3h"/><rect class="wshc33b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dont-sleep" /></template>
<style>
.erd8-3b3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.362 11.692h17.276v24.616H15.362z");
}

.wshc33b9v {
  width: 24.319px;
  height: 39px;
  x: 11.84px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.601px;
  ry: 3.601px;
}

</style>
