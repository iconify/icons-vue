<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3o7arbwb"/><path class="kmxv5q1nx"/><circle class="g4g8lbbfa"/><circle class="d0j32jidf"/><circle class="cbuwjcjyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:interstellar" /></template>
<style>
.cbuwjcjyg {
  cx: 23.597px;
  cy: 21.385px;
  r: 5.855px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d0j32jidf {
  cx: 34.157px;
  cy: 14.227px;
  r: 1.597px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g4g8lbbfa {
  cx: 11.606px;
  cy: 37.903px;
  r: 1.597px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kmxv5q1nx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.02 18.044c.714 3.641-2.766 8.58-8.294 11.772c-6.364 3.675-13.192 3.764-15.25.2c-1.165-2.019-.577-4.895 1.59-7.773");
}

.m3o7arbwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.673 36.283a7.15 7.15 0 0 1-2.111-2.275c-3.308-5.728 2.266-15.137 12.45-21.017s21.119-6.002 24.426-.274q0 0 0 0h0c3.308 5.728-2.266 15.138-12.45 21.017c-4.656 2.689-9.712 4.287-14.153 4.473");
}

</style>
