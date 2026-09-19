<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zuag38bbx"/><rect class="j3s9ivbxi"/><path class="xa0ju_b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:graysky" /></template>
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

.xa0ju_b2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.082 33.188v-.007M5.5 25.149A6.45 6.45 0 0 1 9.185 24a6.5 6.5 0 0 1 5.85 3.677M5.5 29.51c.93.48 1.73 1.19 2.31 2.05c.63-.2 1.3-.32 2-.32c1.3 0 2.51.39 3.51 1.06c.33-.66.77-1.26 1.31-1.76");
}

.zuag38bbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.38 42.5a8.46 8.46 0 0 1-3.55-3.58c-.74.2-1.52.32-2.32.32c-3.92 0-7.24-2.53-8.43-6.05v-.01a8.84 8.84 0 0 1-.04-5.5a8.87 8.87 0 0 1 8.47-6.21c.2 0 .39.02.58.02c2.05-3.16 5.61-5.25 9.66-5.25c.32 0 .63.02.93.04c.96-3.84 3.84-6.93 7.57-8.15M6.03 7.52c7.89 4.98 12.9 9.14 12.34 10.88c-.55 1.69-7.93-.17-12.87-1.62M27.33 5.5c1.033 2.174 1.534 4.44-.038 5.535c-3.207 2.227-5.705-.632-10.068-5.535");
}

</style>
