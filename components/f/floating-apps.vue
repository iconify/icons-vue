<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t9834zbdd"/><path class="r81mr1b8w"/><path class="xj1zuccjf"/><path class="dt74tqnqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:floating-apps" /></template>
<style>
.dt74tqnqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.965 32.443H9.078V14.962h25.071v2.608");
}

.r81mr1b8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.195 24.174h20.312V37.86H19.195z");
}

.t9834zbdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.286 17.78h22.13a2.08 2.08 0 0 1 2.084 2.075V38.81a2.08 2.08 0 0 1-2.075 2.084H18.286a2.08 2.08 0 0 1-2.084-2.075V19.865a2.08 2.08 0 0 1 2.075-2.085z");
}

.xj1zuccjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.965 35.974H8.263A2.76 2.76 0 0 1 5.5 33.217V9.869a2.76 2.76 0 0 1 2.756-2.763h26.707a2.76 2.76 0 0 1 2.764 2.756v7.71");
}

</style>
