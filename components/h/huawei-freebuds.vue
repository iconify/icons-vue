<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ddnvndj2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-freebuds" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ddnvndj2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.904 41.197l-5.803-10.682a4.46 4.46 0 0 1-.27-4.417c1.858-4.214-.195-8.34-3.99-9.33c-4.27-1.116-7.68.68-8.991 2.569c-1.408 2.026-3.316 4.549 1.014 8.587a7.97 7.97 0 0 0 4.89 1.803c1.677.135 3.172.744 3.832 2.456l5.5 11.303");
}

</style>
