<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nc453agpe"/><rect class="ih4p9ndmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bring" /></template>
<style>
.ih4p9ndmu {
  width: 25.999px;
  height: 32.41px;
  x: 11px;
  y: 11.09px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.nc453agpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.18 11.09v-2.2a4.39 4.39 0 0 1 4.43-4.39h8.78a4.39 4.39 0 0 1 4.39 4.39v2.2M15.55 31.56l7.86 4.53l9-15.66m-17.19-9.34h17.56");
}

</style>
