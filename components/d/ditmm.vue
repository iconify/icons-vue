<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle transform="rotate(-50.126 32.949 37.12)" class="dcz35jb_x"/><path class="tbjv09b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ditmm" /></template>
<style>
.dcz35jb_x {
  cx: 32.949px;
  cy: 37.12px;
  r: 0.75px;
  fill: currentColor;
}

.tbjv09b9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.885 32.886l-.055 1.31m-9.283-16.588a9.72 9.72 0 0 1 3.018-6.87a9.78 9.78 0 0 1 7.365-2.31a9.895 9.895 0 0 1 9.562 10.038a9.72 9.72 0 0 1-3.018 6.87c-2.34 1.65-7.439 4.056-7.607 7.987M4.77 15.77a5.612 5.612 0 1 1 10.684-3.435m6.368 19.896a5.612 5.612 0 1 1-10.685 3.436L4.77 15.77m10.684-3.435l6.368 19.896m-3.184-9.948L7.954 25.719");
}

</style>
