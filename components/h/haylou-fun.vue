<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xtkeb5bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:haylou-fun" /></template>
<style>
.xtkeb5bjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.488 27.442c0-7.563-6.205-13.767-13.767-13.767a3.442 3.442 0 0 0 0 6.884a6.83 6.83 0 0 1 6.884 6.883v11.616a3.442 3.442 0 0 0 6.883 0V8.943a3.442 3.442 0 0 0-6.883 0v6.594M8.512 20.558c0 7.563 6.205 13.767 13.767 13.767a3.442 3.442 0 0 0 0-6.884a6.83 6.83 0 0 1-6.884-6.883V8.942a3.442 3.442 0 0 0-6.883 0v30.115a3.442 3.442 0 0 0 6.883 0v-6.594");
}

</style>
