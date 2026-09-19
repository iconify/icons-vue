<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lbq1b4uwe"/><path class="p6bvpmbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:glitch-lab" /></template>
<style>
.lbq1b4uwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.884 34.73a8.197 8.197 0 0 0 9.76-9.76l6.562-6.562a16.775 16.775 0 0 1-22.884 22.885Z");
}

.p6bvpmbag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.782 35.833a16.772 16.772 0 1 1 22.884-22.885l-6.562 6.562a8.191 8.191 0 1 0-9.76 9.76Z");
}

</style>
