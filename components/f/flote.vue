<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q8av9xbpq"/><path class="fjf1kj2oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flote" /></template>
<style>
.fjf1kj2oe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.217 9.22V6.795l-6.838 4.267l6.747-1.347M5.547 38.56L42.5 34.293s-.388 6.837-6.79 6.837c-7.08 0-6.934-4.752-6.934-4.752s-1.115 4.222-5.092 4.827H6.614a2.64 2.64 0 0 1-1.067-2.645");
}

.q8av9xbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.217 33.758c3.637-3.928 4.365-18.67 0-24.538c9.117 3.83 16.973 13.87 18.186 22.792L7.948 35.407c6.886-8.39 10.135-14.403 12.269-26.187Z");
}

</style>
