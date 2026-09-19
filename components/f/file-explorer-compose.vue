<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u4zr43bhi"/><path class="m6q-2tjcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:file-explorer-compose" /></template>
<style>
.m6q-2tjcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.967 24A5.96 5.96 0 0 1 24 29.955h0A5.96 5.96 0 0 1 18.033 24h0A5.96 5.96 0 0 1 24 18.045h0A5.96 5.96 0 0 1 29.967 24");
}

.u4zr43bhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.213 34.25L24 44.5l17.787-10.25v-20.5L24 3.5L6.213 13.75zm.437-20.248l11.967 6.895M24 44V30.203m17.35-16.201l-11.967 6.895");
}

</style>
