<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e-si2ocwh"/><path class="rofzymbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freebox-files" /></template>
<style>
.e-si2ocwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.065 36.026a6.474 6.474 0 1 1-12.948 0a6.474 6.474 0 0 1 12.948 0m-8.324 0h2.405");
}

.rofzymbyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.741 39.725v-7.399h3.7M8.6 42.5l13.947-27.972c2.47-4.955 9.052-11.01 16.852-8.4M11.587 18.119h20.194");
}

</style>
