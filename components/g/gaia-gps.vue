<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qn3c72b9z"/><path class="l63he--aa"/><path class="v5sd9pbdh"/><path class="yhvbz1bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gaia-gps" /></template>
<style>
.l63he--aa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.01 16.664l5.387 2.767l-5.387 2.84l-5.308-2.816z");
}

.qn3c72b9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.01 41.29l19.49-9.757l-9.51-14.226l-2.148 1.21L24.01 6.71l-5.11 7.706l-2.124-1.161L4.5 31.558zm0-34.58v34.58");
}

.v5sd9pbdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 24.716l4.928-2.568l3.58 1.85L24 28.224L15.59 24l3.408-1.877z");
}

.yhvbz1bvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.05 30.817l7.421-3.804l4.397 2.075l-11.819 6.15l-11.868-6.1l4.249-2.15z");
}

</style>
