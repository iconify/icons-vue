<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z8ib-3jsp"/><path class="d045uivat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a5etools" /></template>
<style>
.d045uivat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.31 33.03c1.5 1.257 2.955 1.833 6.592 1.833h.784a7.02 7.02 0 0 0 7.018-7.018h0a7.02 7.02 0 0 0-7.018-7.018H11.31v-7.69h13.566m11.27 14.272a4.15 4.15 0 0 1-3.61 2.096h0a4.155 4.155 0 0 1-4.155-4.155v-2.7a4.155 4.155 0 0 1 4.155-4.155h0a4.155 4.155 0 0 1 4.154 4.155V24h-8.31");
}

.z8ib-3jsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.48 5.5a2 2 0 0 0-2 2v33a2 2 0 0 0 2 2h33.04a2 2 0 0 0 2-2v-33a2 2 0 0 0-2-2Z");
}

</style>
