<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c69remmqt"/><path class="zw-2nxbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dpd" /></template>
<style>
.c69remmqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 3.5l17.754 10.25v20.5L24 44.5L6.246 34.25v-20.5z");
}

.zw-2nxbnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.247 13.75L24 24v14.302M41.754 13.75l-12.386 7.151");
}

</style>
