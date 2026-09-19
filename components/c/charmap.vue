<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p14zi8bqu"/><path class="uti9wtbhz"/><path class="sniys1rgx"/><path class="g5fss3kou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:charmap" /></template>
<style>
.g5fss3kou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.3 30a1.54 1.54 0 0 1-1.5-1.5v-8.4m-4.9-2l2.4-.8M7.246 41.161l3.387-4.365M7.188 6.94l2.977 2.449m30.624 31.772l-3.387-4.365M40.847 6.94L37.87 9.39");
}

.p14zi8bqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.35 5.45h27.3a4.23 4.23 0 0 1 4.2 4.2v28.7a4.23 4.23 0 0 1-4.2 4.2h-27.3a4.23 4.23 0 0 1-4.2-4.2V9.65a4.29 4.29 0 0 1 4.2-4.2");
}

.sniys1rgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.8 26.3a3.69 3.69 0 0 1-3.7 3.7a3.69 3.69 0 0 1-3.7-3.7v-2.4a3.69 3.69 0 0 1 3.7-3.7a3.69 3.69 0 0 1 3.7 3.7");
}

.uti9wtbhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.65 8.2h22.7a3.33 3.33 0 0 1 3.3 3.3v22.7a3.33 3.33 0 0 1-3.3 3.3h-22.7a3.33 3.33 0 0 1-3.3-3.3V11.5a3.4 3.4 0 0 1 3.3-3.3");
}

</style>
