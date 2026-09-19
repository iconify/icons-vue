<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jaa0jo28t"/><circle class="bnws29b1l"/><path class="il7cebwlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bikecitizens" /></template>
<style>
.bnws29b1l {
  cx: 32.125px;
  cy: 28.875px;
  r: 1.625px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.il7cebwlk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.125 17.5A11.375 11.375 0 1 1 20.75 28.875m-16.25 0a8.125 8.125 0 0 1 16.25 0m-5.688-11.349a4.875 4.875 0 1 1 2.42-4.647");
}

.jaa0jo28t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.274 7.75h-13l9.165 19.655M35.274 7.75v3.245");
}

</style>
