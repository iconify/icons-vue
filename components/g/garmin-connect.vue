<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s15gkwbmm"/><circle class="c8c-a65gx"/><path class="e0bq4ty8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:garmin-connect" /></template>
<style>
.c8c-a65gx {
  cx: 9.5px;
  cy: 9.433px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e0bq4ty8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.176 8.115a2.68 2.68 0 0 0-2.82-2.678c-1.447.076-2.532 1.377-2.532 2.83v2.484A2.68 2.68 0 0 0 9.5 13.433h0c1.478 0 2.676-1.2 2.676-2.682H9.5m25.097 11.773c-1.746-4.128-5.833-7.024-10.596-7.024c-5.841 0-10.666 4.355-11.403 9.996m0 3.008c.737 5.64 5.561 9.996 11.403 9.996c4.75 0 8.828-2.88 10.582-6.99");
}

.s15gkwbmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.176V38.5a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4H15.291");
}

</style>
