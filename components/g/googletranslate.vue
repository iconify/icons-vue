<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i_zez2bhk"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:googletranslate" /></template>
<style>
.i_zez2bhk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.5 42.6L32.3 5.5M30 22.4l10.1 2.4m-3.8-4.6v3.6M24.7 40c2.6-4 5.7-7.5 13.6-10.7m-9.8-2.9C32.1 29.6 35 33.6 37 38M14.8 15h4.9c0 2.7-2.1 4.9-4.8 5q0 0 0 0c-2.8 0-5-2.3-5-5s2.3-5 5-5c.8 0 1.7.2 2.4.6");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

</style>
