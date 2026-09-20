<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fozs7-uad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:even" /></template>
<style>
.fozs7-uad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 8.583H42.5v6.167H17.833zm0 12.182H42.5v6.167H17.833zm0 12.182H42.5v6.167H17.833zm0-12.002v-6.167h-6.166V8.583H5.5v30.834h6.167V33.25h6.166v-6.167h-6.166v-6.138z");
}

</style>
