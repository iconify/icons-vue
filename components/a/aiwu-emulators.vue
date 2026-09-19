<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wew_62toe"/><circle class="scjuqt_cp"/><path class="lgl40_bve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aiwu-emulators" /></template>
<style>
.lgl40_bve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.243 5.5h4.743c5.124 0 9.25 4.126 9.25 9.25S20.11 24 14.868 24S5.5 28.126 5.5 33.25s4.126 9.25 9.25 9.25h18.5c5.125 0 9.25-4.125 9.25-9.25S38.375 24 33.368 24s-9.132-4.125-9.132-9.25s4.125-9.25 9.25-9.25h4.507M15.75 29.05v8.4m-4.2-4.2h8.375");
}

.scjuqt_cp {
  cx: 32.25px;
  cy: 33.25px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wew_62toe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.312 38.255a4.63 4.63 0 0 1-4.625 0");
}

</style>
