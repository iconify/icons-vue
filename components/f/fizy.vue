<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="h6yd8gxxi"/><path class="e03lvbc2e"/><circle class="zqud3ub3l"/><path class="mh5txkbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fizy" /></template>
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

.e03lvbc2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.141 21.321v3.536c0 1.179-.964 2.143-2.143 2.143s-2.143-.964-2.143-2.143v-3.536m-6.646 0h4.285l-4.285 5.786h4.285");
}

.h6yd8gxxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.141 24.964v2.893A2.15 2.15 0 0 1 31.998 30c-.643 0-1.178-.214-1.5-.643");
}

.mh5txkbxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.638 21.321v5.786m-5.494 0v-7.179c0-.857.643-1.5 1.5-1.5c.75 0 1.179.215 1.5.643m-4.285 2.25h3");
}

.zqud3ub3l {
  cx: 20.638px;
  cy: 18.75px;
  r: 0.75px;
  fill: currentColor;
}

</style>
