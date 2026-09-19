<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g4wjpsbjp"/><path class="bag4m3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-tuta-17" /></template>
<style>
.bag4m3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

.g4wjpsbjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.937 22.78l4.205-1.98m0 0l-4.403 14.4m6.863 0l12.143-14.4h-9.54");
}

</style>
