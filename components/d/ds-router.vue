<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="k6-9_0bqv"/><path class="tx5p-xvyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ds-router" /></template>
<style>
.k6-9_0bqv {
  width: 37px;
  height: 16.033px;
  x: 5.5px;
  y: 26.132px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.tx5p-xvyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.681 31.873h2.907v2.907h-2.907zm-6.475 0h2.907v2.907h-2.907zM16.51 17.43c1.885-1.965 4.555-3.174 7.493-3.174s5.593 1.21 7.494 3.173M11.01 11.02c3.394-3.206 7.95-5.185 12.993-5.185s9.615 1.98 12.993 5.2");
}

</style>
