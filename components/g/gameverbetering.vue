<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="dva8aybez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gameverbetering" /></template>
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

.dva8aybez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.718 9.5v8.61l4.04 4.328l4.219-4.283V9.5zm18.437 10.752v7.94h-7.902l-4.42-4.037l3.93-3.903zm-14.397 5.89l4.174 4.105V38.5h-7.946v-8.253zm-5.743-6.069l3.772 4.082l-3.862 4.216h-8.08v-8.298z");
}

</style>
