<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="io6dpm5mh"/><path class="x-4v47rve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:breeno" /></template>
<style>
.io6dpm5mh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.692 24c-2.437 7.562-10.542 13.692-18.104 13.692S7.872 31.562 10.308 24S20.85 10.309 28.411 10.309s11.717 6.13 9.28 13.691");
}

.x-4v47rve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.723 26.24c4.191 7.054 2.788 11.77-3.135 10.532c-5.922-1.237-14.12-7.958-18.311-15.012s-2.788-11.77 3.135-10.532c5.922 1.237 14.12 7.958 18.311 15.012");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
