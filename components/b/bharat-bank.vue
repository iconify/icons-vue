<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zo4esbbbb"/><path class="m5laz9bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bharat-bank" /></template>
<style>
.m5laz9bew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 24.793a2.44 2.44 0 0 1-2.439 2.439h0a2.44 2.44 0 0 1-2.439-2.44v-1.585a2.44 2.44 0 0 1 2.439-2.439h0a2.44 2.44 0 0 1 2.439 2.44m0 4.024v-6.464m-20.122 6.464v-4.025a2.44 2.44 0 0 0-2.439-2.439h0a2.44 2.44 0 0 0-2.439 2.44m0 4.024v-6.464M23.239 26a2.44 2.44 0 0 1-2.12 1.232h0a2.44 2.44 0 0 1-2.439-2.44v-1.585a2.44 2.44 0 0 1 2.44-2.439h0a2.44 2.44 0 0 1 2.438 2.44V24H18.68");
}

.zo4esbbbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-8.471 15.268l-4.878 6.464m4.878 0l-4.878-6.464");
}

</style>
