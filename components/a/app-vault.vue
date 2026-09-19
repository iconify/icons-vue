<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e7y5q50za"/><path class="uficjmb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:app-vault" /></template>
<style>
.e7y5q50za {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 11h-33a2 2 0 0 0-2 2v22a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2V13a2 2 0 0 0-2-2M39 10V6.5a1 1 0 0 0-1-1H10a1 1 0 0 0-1 1V10a1 1 0 0 0 1 1h28a1 1 0 0 0 1-1M9 38v3.5a1 1 0 0 0 1 1h28a1 1 0 0 0 1-1V38a1 1 0 0 0-1-1H10a1 1 0 0 0-1 1");
}

.uficjmb1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 15h7v7h-7z");
}

</style>
