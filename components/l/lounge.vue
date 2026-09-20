<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lin7w-n5d"/><path class="ow8277b9h"/><path class="il6u-yejm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lounge" /></template>
<style>
.il6u-yejm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25 24.35h13.61a1 1 0 0 1 1 1v5H24v-5a1 1 0 0 1 1-1M8.38 30.41h3.07v3.73H8.38zm28.17 0h3.07v3.73h-3.07z");
}

.lin7w-n5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.39 24.35H23a1 1 0 0 1 1 1v5H8.38v-5a1 1 0 0 1 1.01-1");
}

.ow8277b9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.38 25.36V15.28a1.41 1.41 0 0 1 1.41-1.41h12.8A1.41 1.41 0 0 1 24 15.28v10.08m0 0V15.28a1.41 1.41 0 0 1 1.41-1.41h12.8a1.41 1.41 0 0 1 1.41 1.41v10.08M5.36 19.57h2.16a.86.86 0 0 1 .86.86v10H5.57a1.07 1.07 0 0 1-1.07-1.1v-8.9a.86.86 0 0 1 .86-.86m37.07 10.84h-2.81v-10a.86.86 0 0 1 .86-.86h2.16a.86.86 0 0 1 .86.86v8.9a1.07 1.07 0 0 1-1.07 1.07Z");
}

</style>
