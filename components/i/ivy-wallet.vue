<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m856pnbfo"/><path class="sk_n8qbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ivy-wallet" /></template>
<style>
.m856pnbfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.312 38.862H11.688A6.32 6.32 0 0 1 5.5 33.817h0a48.7 48.7 0 0 1 0-19.634h0a6.32 6.32 0 0 1 6.188-5.045h24.624a6.32 6.32 0 0 1 6.188 5.045h0a48.7 48.7 0 0 1 0 19.634h0a6.32 6.32 0 0 1-6.188 5.045");
}

.sk_n8qbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.5 18L24 30l7.5-12");
}

</style>
