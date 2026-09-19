<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mbsy3tbth"/><path class="pbzmbh85w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:annas-archive" /></template>
<style>
.mbsy3tbth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.753 5.565L42.5 42.398l-11.303.037l-1.915-7.252H18.718l-1.915 7.252L5.5 42.398L17.247 5.565z");
}

.pbzmbh85w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.376 27.27L24 14.588L20.624 27.27z");
}

</style>
