<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="d1e08d4se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:behance" /></template>
<style>
.d1e08d4se {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.005 29.651a3.78 3.78 0 0 1-7.063-1.872v-2.456a3.78 3.78 0 1 1 7.559 0v1.228h-7.56M19.736 24a3.78 3.78 0 1 1 0 7.559H13.5V16.442h6.236a3.78 3.78 0 1 1 0 7.558m0 0H13.5m13.441-7.559H34.5");
}

.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

</style>
