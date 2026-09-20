<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xdhiexq0j"/><path class="um7rzrdbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:esselunga" /></template>
<style>
.um7rzrdbr {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.858 30.33h15.85l1.522-1.52v-3.487l-1.521-1.521H17.29l-1.52-1.522v-3.09l1.52-1.52H42.5");
}

.xdhiexq0j {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29c2.216 0 4-1.784 4-4v-29c0-2.216-1.784-4-4-4h-29c-2.216 0-4 1.784-4 4v29c0 2.216 1.784 4 4 4");
}

</style>
