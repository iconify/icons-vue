<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ryxyldbss"/><path class="akoz2pt5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geometry-dash-subzero" /></template>
<style>
.akoz2pt5b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.222 23.528a3.561 3.561 0 1 0 6.52-1.448zm11.306-11.306a3.561 3.561 0 1 1-1.448 6.52zm9.188 16.976v-4.16h2.676v-2.437l-.77-3.971h-1.796v2.23h-3.775v4.068h-4.123v4.123H20.86v3.775h-2.23v1.796l3.971.77h2.437v-2.676h4.16V29.18z");
}

.ryxyldbss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5L44.5 24L24 44.498l-20.5-20.5z");
}

</style>
