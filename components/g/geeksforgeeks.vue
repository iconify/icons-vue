<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g9o7n05tw"/><path class="yh4m1yimd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geeksforgeeks" /></template>
<style>
.g9o7n05tw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.994 24H43.5a9.751 9.751 0 1 1-2.856-6.894");
}

.yh4m1yimd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.006 24H4.5a9.751 9.751 0 1 0 2.857-6.894");
}

</style>
