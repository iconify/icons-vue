<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wd2mp0w4t"/><path class="vk1u2cbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cooltra" /></template>
<style>
.vk1u2cbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.727 24.18c0-13.838 24.718-8.223 24.718 0c0 7.66-24.718 13.681-24.718 0m34.241-3.626a16.2 16.2 0 0 1 0 6.903q4.61-3.457 0-6.903");
}

.wd2mp0w4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.4 12.737Q40.714 24 30.4 35.263");
}

</style>
