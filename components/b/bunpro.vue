<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="evpc3ybfk"/><path class="d73re3l_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bunpro" /></template>
<style>
.d73re3l_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14v-2m-8.194 8c1.375 3.625 3.571 7.522 6.63 10.904m4.445 4.03c1.64 1.202 3.13 2.245 4.72 3.067M33.166 17c-2.56 9.555-9.486 23-25.667 23h-2V8h37v32h-4m-.831-23H39.5m-31 0h26.167");
}

.evpc3ybfk {
  cx: 34.668px;
  cy: 14.001px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
