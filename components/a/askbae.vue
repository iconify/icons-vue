<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8-_1ovuv"/><circle class="w8nozx66d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:askbae" /></template>
<style>
.p8-_1ovuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.014 12.734A13 13 0 0 1 30.5 11a13 13 0 0 1 13 13a13 13 0 0 1-13 13a13 13 0 0 1-6.513-1.75");
}

.w8nozx66d {
  cx: 17.5px;
  cy: 24px;
  r: 13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
