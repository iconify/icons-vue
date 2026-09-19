<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kc3wg7b7w"/><circle class="cpk0fnbgt"/><circle class="j5ahyib_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:activitywatch" /></template>
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

.j5ahyib_q {
  cx: 24px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kc3wg7b7w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.725 22.688l5.564-9.637m-7.542 11.772L9.913 33.917m13.484-11.29l-5.93-12.74l-6.46 14.013m2.18-4.73h8.6m16.223 4.759l-3.501 14l-3.5-14l-3.5 14l-3.12-12.481");
}

</style>
