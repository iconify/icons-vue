<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zzgjxybrw"/><path class="pkcjcsb5z"/><path class="cho--bcdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:file-commander" /></template>
<style>
.cho--bcdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.706 22.5L24.312 28l5.394 5.5");
}

.pkcjcsb5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.295h-39v18.72a2.18 2.18 0 0 0 2.16 2.2h34.66a2.18 2.18 0 0 0 2.18-2.18v-.02ZM18.294 22.5h7.024M18.294 28h2.743m-2.743-5.5v11");
}

.zzgjxybrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13.015H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9a2.18 2.18 0 0 0-2.18 2.18v7.34h39v-3.42a1.83 1.83 0 0 0-1.79-1.87Z");
}

</style>
