<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kemlxw0ct"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:canva" /></template>
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

.kemlxw0ct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.563 22.611L31.341 28.5l-2.223-5.889M20.9 26.278a2.23 2.23 0 0 1-2.223 2.222a2.23 2.23 0 0 1-2.222-2.222v-1.445a2.23 2.23 0 0 1 2.222-2.222a2.23 2.23 0 0 1 2.223 2.222m0 3.667v-5.889m6.63 5.889v-3.667a2.23 2.23 0 0 0-2.222-2.222a2.23 2.23 0 0 0-2.222 2.222V28.5m0-3.667v-2.222m-8.67 2.889za2.99 2.99 0 0 1-3 3a2.99 2.99 0 0 1-3-3v-3a2.99 2.99 0 0 1 3-3a2.895 2.895 0 0 1 2.89 3m25.278 3.778A2.23 2.23 0 0 1 37.36 28.5a2.23 2.23 0 0 1-2.222-2.222v-1.445a2.23 2.23 0 0 1 2.222-2.222a2.23 2.23 0 0 1 2.223 2.222m.001 3.667v-5.889");
}

</style>
