<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u43yjqw8q"/><path class="q3jffx5im"/><path class="unm4jkbkj"/><path class="vgtu2mb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-my-business" /></template>
<style>
.q3jffx5im {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.858 7.094H9.142a2 2 0 0 0-1.941 1.52L4.5 19.557h9.75m9.75 0a4.875 4.875 0 0 1-9.75 0m0 0a4.875 4.875 0 0 1-9.75 0m29.25 0H24V7.094h8.142zM32.142 7.094h6.716a2 2 0 0 1 1.941 1.52L43.5 19.557h-9.75m-9.75 0a4.875 4.875 0 0 0 9.75 0m0 0a4.875 4.875 0 0 0 9.75 0");
}

.u43yjqw8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 19.557H24V7.094h-8.142z");
}

.unm4jkbkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.325 23.977v14.93a2 2 0 0 0 2 2h29.35a2 2 0 0 0 2-2v-14.93");
}

.vgtu2mb4k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 33.569h3.956a3.977 3.977 0 0 1-3.88 4.072l-.077.001a4.073 4.073 0 1 1 0-8.147a4 4 0 0 1 2.02.536");
}

</style>
