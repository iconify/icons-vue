<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hefbipbmh"/><path class="bag4m3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-tuta-18" /></template>
<style>
.bag4m3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

.hefbipbmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.885 22.78l4.205-1.98m0 0l-4.403 14.4M29.891 28h-2.34c-1.98 0-4.095 1.62-4.7 3.6h0c-.605 1.98.52 3.6 2.5 3.6h2.34c1.98 0 4.095-1.62 4.7-3.6h0c.605-1.98-.52-3.6-2.5-3.6m0 0c1.98 0 4.096-1.62 4.701-3.6h0c.605-1.98-.52-3.6-2.5-3.6h-2.34c-1.98 0-4.095 1.62-4.7 3.6h0c-.605 1.98.52 3.6 2.5 3.6");
}

</style>
