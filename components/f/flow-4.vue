<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tlvnx39hh"/><path class="onyk7siaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flow-4" /></template>
<style>
.onyk7siaa {
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 2.988 2.988;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.814 13.132l13.678-3.02a3.297 3.297 0 0 1 4.008 3.22v21.336a3.297 3.297 0 0 1-4.008 3.22l-13.678-3.02");
}

.tlvnx39hh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.285 16.465L8.508 10.113a3.297 3.297 0 0 0-4.008 3.22v21.335a3.297 3.297 0 0 0 4.008 3.22l28.777-6.353a3.3 3.3 0 0 0 2.587-3.22v-8.63a3.3 3.3 0 0 0-2.587-3.22");
}

</style>
