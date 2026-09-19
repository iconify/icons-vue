<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rwjrpobuw"/><circle class="h6d5p1bpj"/><circle class="s2c393ypg"/><circle class="mx8_au4hu"/><circle class="adytyvb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:burrito" /></template>
<style>
.adytyvb4w {
  cx: 24px;
  cy: 31.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.h6d5p1bpj {
  cx: 24px;
  cy: 16.5px;
  r: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mx8_au4hu {
  cx: 24px;
  cy: 16.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rwjrpobuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 4.5h9v39h-9z");
}

.s2c393ypg {
  cx: 24px;
  cy: 31.5px;
  r: 12px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
