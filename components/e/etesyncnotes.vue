<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h38wt6bjl"/><path class="ei1yxobdb"/><path class="qibpakmer"/><path class="dpfhaebye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:etesyncnotes" /></template>
<style>
.dpfhaebye {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 23.33v2.03l-2.79-2.79L24 19.79zm0 9.11v-2.02l2.79 2.78L24 35.99z");
}

.ei1yxobdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.24 12.71H6.76v28a2.85 2.85 0 0 0 2.86 2.86h28.74a2.86 2.86 0 0 0 2.88-2.85Z");
}

.h38wt6bjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 15.94l-3.5 3.5h-4.94v4.95l-3.5 3.5l3.5 3.49v4.95h4.94l3.5 3.5l3.5-3.5h4.94v-4.95l3.5-3.49l-3.5-3.5v-4.95H27.5Zm14.36-9.75h-1.07a1.79 1.79 0 0 0-3.57 0H14.3a1.79 1.79 0 0 0-3.57 0H9.66A2.88 2.88 0 0 0 6.76 9v3.68h34.48V9.06a2.87 2.87 0 0 0-2.86-2.87Z");
}

.qibpakmer {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.47 30.9A5.39 5.39 0 0 0 24 22.5m-4.47 2.37A5.4 5.4 0 0 0 24 33.28");
}

</style>
