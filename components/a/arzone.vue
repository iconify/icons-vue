<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aazlz10bj"/><path class="g4njejbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arzone" /></template>
<style>
.aazlz10bj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4h-29c-2.2 0-4 1.8-4 4z");
}

.g4njejbcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.1 32V16h5.2c3 0 5.4 2.4 5.4 5.4c0 2.9-2.4 5.3-5.4 5.4h-5.2m5.2-.1l5.3 5.3m-23.3 0l5.3-16m5.1 16l-5.1-16M21 26.6h-6.9");
}

</style>
