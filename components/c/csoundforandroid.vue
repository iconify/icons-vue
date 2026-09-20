<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="h1nqd-dkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:csoundforandroid" /></template>
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

.h1nqd-dkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.43 31.87a5.25 5.25 0 0 1-4.56 2.65a5.26 5.26 0 0 1-5.26-5.26v-3.42a5.26 5.26 0 0 1 5.26-5.26a5.25 5.25 0 0 1 4.56 2.64v1.25m3.44 6.42v1.32A5.89 5.89 0 0 0 29 34.52h3.11a5.26 5.26 0 0 0 5.25-5.26A5.25 5.25 0 0 0 32.14 24H28.7a5.25 5.25 0 0 1-5.24-5.26a5.26 5.26 0 0 1 5.24-5.26h3.12A5.89 5.89 0 0 1 37 15.79v1.32");
}

</style>
