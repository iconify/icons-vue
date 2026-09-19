<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ssprhabsd"/><path class="mi6x78k3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:baresip" /></template>
<style>
.mi6x78k3j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 43.5h23a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4h-23a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4");
}

.ssprhabsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.25 26.713a7.75 7.75 0 0 1 15.5 0v5.037a7.75 7.75 0 0 1-15.5 0m0-23.25v31m5.328-27.125h7.75M25.453 8.5v7.75");
}

</style>
