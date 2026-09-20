<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zo4esbbbb"/><path class="wjdo5o7ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bharat-bank" /></template>
<style>
.wjdo5o7ba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 24.793a2.439 2.439 0 0 1-4.878 0v-1.586a2.439 2.439 0 0 1 4.878 0m0 4.025v-6.464m-20.122 6.464v-4.025a2.439 2.439 0 0 0-4.878 0m0 4.025v-6.464M23.239 26a2.439 2.439 0 0 1-4.558-1.208v-1.585a2.439 2.439 0 0 1 4.878 0V24H18.68");
}

.zo4esbbbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-8.471 15.268l-4.878 6.464m4.878 0l-4.878-6.464");
}

</style>
