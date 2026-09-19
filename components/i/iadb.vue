<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l5-epwbkj"/><path class="bnxmhm47m"/><circle class="e7p99ubpx"/><circle class="ch4zqsbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iadb" /></template>
<style>
.bnxmhm47m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.727 34.491l2.926 10.927l-2.25-8.402c-.437-1.629-1.804-1.999-2.87-1.713s-1.904 1.293-1.514 2.75l1.855 7.365C9.6 43.781 2.5 34.152 2.5 24.082c0-11.874 9.626-21.5 21.5-21.5s21.5 9.626 21.5 21.5c0 1.588-.176 3.172-.525 4.721M36.3 20.841l1.05-3.808m-10.097 6.233l-2.944-2.97");
}

.ch4zqsbmt {
  cx: 28.685px;
  cy: 28.271px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e7p99ubpx {
  cx: 37.561px;
  cy: 25.894px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l5-epwbkj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.726 34.497c-1.573-5.868 1.91-11.9 7.778-13.472s11.9 1.91 13.472 7.778z");
}

</style>
