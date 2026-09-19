<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="kpabhw2pw"/><path class="xpro3ibdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jsho" /></template>
<style>
.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.kpabhw2pw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 23.09v10.82c0 2.719 5.271 5.66 10.154 0m.388-17.846v10.82c0 2.719 5.271 5.66 10.154 0M16.284 22.73c1.734.763 2.802 1.914 2.802 1.914m-4.056-.268c1.735.763 2.803 1.914 2.803 1.914m14.403-15.433v8.822c0 4.182-4.744 4.14-4.744 1.373c0-3.413 5.763-1.706 10.008.374");
}

.xpro3ibdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.236 14.727c1.893.29 4.702-.396 4.702-.396");
}

</style>
