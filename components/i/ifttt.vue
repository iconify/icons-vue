<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sr-krn6qx"/><path class="ivqk8obde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ifttt" /></template>
<style>
.ivqk8obde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.8 27.1v-6.2h3m8.6 0h4.1m-2 6.2v-6.2m4.4 0H37m-2.1 6.2v-6.2");
}

.sr-krn6qx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4M11 20.9v6.2m9.1-6.2h4.1m-2.1 6.2v-6.2M14.8 24h2");
}

</style>
