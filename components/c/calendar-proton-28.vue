<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yhburfbkx"/><path class="f6_7b22_l"/><path class="wtoegrbgv"/><path class="orx8z1bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-proton-28" /></template>
<style>
.f6_7b22_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 25.793v-13.93a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.275a4 4 0 0 0 4 4");
}

.orx8z1bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.207 40.138V15.819a3.14 3.14 0 0 0-3.138-3.138H4.5");
}

.wtoegrbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.138V11.862a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v24.276a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

.yhburfbkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.854 23.91a4.943 4.943 0 0 1 4.815-5a4.976 4.976 0 0 1 3.518 8.519c-2.037 1.666-8.333 6.481-8.333 6.481h9.815m8.434-7.5h-2.438a3.76 3.76 0 0 0-3.75 3.75a3.76 3.76 0 0 0 3.75 3.75h2.438a3.76 3.76 0 0 0 3.75-3.75a3.76 3.76 0 0 0-3.75-3.75m0 0a3.76 3.76 0 0 0 3.75-3.75a3.76 3.76 0 0 0-3.75-3.75h-2.438a3.76 3.76 0 0 0-3.75 3.75a3.76 3.76 0 0 0 3.75 3.75");
}

</style>
