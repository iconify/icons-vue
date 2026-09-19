<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8whpqbas"/><path class="hmp1drb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adoberush" /></template>
<style>
.hmp1drb9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.94 33.89V14h6.65a6.67 6.67 0 0 1 0 13.33H9.94m6.65.04l6.58 6.59m14.89-5.05a5 5 0 0 1-5 5h0a5 5 0 0 1-5-5v-8m10 12.98V20.94");
}

.p8whpqbas {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 5.5h-33a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h33a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2Z");
}

</style>
