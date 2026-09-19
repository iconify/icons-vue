<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mmy-ewvpa"/><circle class="f71wp2b1t"/><path class="tsp1mp6ah"/><path class="e0rbkkbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:efaas" /></template>
<style>
.e0rbkkbbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.738 6.006v18.407a9.36 9.36 0 0 1-5.778 8.65a9.36 9.36 0 0 1-10.2-2.03a9.365 9.365 0 0 1 6.618-15.983m18.379 9.598v-11.34");
}

.f71wp2b1t {
  cx: 23.379px;
  cy: 24.413px;
  r: 0.75px;
  fill: currentColor;
}

.mmy-ewvpa {
  cx: 41.757px;
  cy: 6.443px;
  r: 0.75px;
  fill: currentColor;
}

.tsp1mp6ah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.371 31.417c-3.515 8.534-12.81 13.138-21.726 10.76s-14.686-11-13.488-20.152S14.152 6.029 23.38 6.029");
}

</style>
