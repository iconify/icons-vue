<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wd8xhjwhw"/><path class="htd3y-blf"/><circle class="zerg3u0jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:francetv" /></template>
<style>
.htd3y-blf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36 17.899l-4.557 12.075l-4.556-12.075m-6.054-3.873v13.67c0 1.367.912 2.278 2.279 2.278h.683");
}

.wd8xhjwhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M18.555 17.899h8.332");
}

.zerg3u0jp {
  cx: 14.636px;
  cy: 23.937px;
  r: 2.636px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
