<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y3ehmyo3q"/><path class="r5h3jvbhf"/><path class="xb5-xbcei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:concentration" /></template>
<style>
.r5h3jvbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.04 31.278a9.538 9.538 0 1 1 15.818.323");
}

.xb5-xbcei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.914 22.71c-3.776-5.018-2.77-12.147 2.249-15.924C22.18 3.01 29.31 4.016 33.086 9.034a11.37 11.37 0 0 1 .054 13.604");
}

.y3ehmyo3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.841 26.485c4.698 0 8.508 3.81 8.508 8.507S28.54 43.5 23.841 43.5a8.508 8.508 0 0 1 0-17.015");
}

</style>
