<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n4hfftuom"/><path class="w03dykbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cartoon-network" /></template>
<style>
.n4hfftuom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.132 30.753V17.247L42.5 30.753V17.247m-22.158 8.977v.055a4.474 4.474 0 1 1-8.948 0v-4.558a4.474 4.474 0 1 1 8.948 0v.055");
}

.w03dykbfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 13.632h20.736v20.736H5.5z");
}

</style>
