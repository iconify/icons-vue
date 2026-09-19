<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wz4anbbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:glassdoor" /></template>
<style>
.wz4anbbdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 10.5v20h6v-20h21a6 6 0 0 0-6-6h-15a6 6 0 0 0-6 6m21 27h-21a6 6 0 0 0 6 6h15a6 6 0 0 0 6-6v-20h-6z");
}

</style>
