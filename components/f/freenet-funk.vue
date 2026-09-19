<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r3lewd71a"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freenet-funk" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.r3lewd71a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.26 38.5V25.287L23.014 38.5V25.287M25.152 9.5v8.754c0 2.477 1.982 4.459 4.294 4.459s4.294-1.982 4.294-4.46V9.5m-19.476 6.607h4.295m-4.295 6.606V9.5h6.607m5.932 15.787V38.5m0-4.625l6.937-8.588m0 13.213l-5.285-6.607");
}

</style>
