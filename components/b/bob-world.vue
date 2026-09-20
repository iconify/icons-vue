<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yr_ivfb7b"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bob-world" /></template>
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

.yr_ivfb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.59 29.161l-1.781 7.01l-1.78-7.01l-1.78 7.01l-1.781-7.01m10.119 7.009za1.77 1.77 0 0 1-1.78-1.752V33.28a1.77 1.77 0 0 1 1.78-1.752a1.77 1.77 0 0 1 1.78 1.752v1.14a1.77 1.77 0 0 1-1.78 1.752m3.789-2.892a1.77 1.77 0 0 1 1.78-1.753m-1.78 0v4.644m3.625-7.01v7.01m5.531-2.891a1.77 1.77 0 0 0-1.78-1.753a1.77 1.77 0 0 0-1.78 1.752v1.14a1.77 1.77 0 0 0 1.78 1.752a1.77 1.77 0 0 0 1.78-1.753m0 1.753v-7.01M25 26.517za3.64 3.64 0 0 1-3.581-3.672v-2.387A3.64 3.64 0 0 1 25 16.786a3.64 3.64 0 0 1 3.581 3.672v2.387A3.64 3.64 0 0 1 25 26.517m-14.002-6.059a3.64 3.64 0 0 1 3.58-3.672a3.64 3.64 0 0 1 3.582 3.672v2.387a3.64 3.64 0 0 1-3.581 3.672a3.64 3.64 0 0 1-3.581-3.672m0 3.672V11.829m20.842 8.629a3.64 3.64 0 0 1 3.581-3.672a3.64 3.64 0 0 1 3.581 3.672v2.387a3.64 3.64 0 0 1-3.58 3.672a3.64 3.64 0 0 1-3.582-3.672m0 3.672V11.829");
}

</style>
