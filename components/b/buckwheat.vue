<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cy8q42aet"/><path class="bvlrw_b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:buckwheat" /></template>
<style>
.bvlrw_b-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.371 5.57c-4.418 18.053-6.16 30.307-19.218 33.913");
}

.cy8q42aet {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.366 5.5S-6.241 15.648 9.757 32.142C28.017 50.967 50.24 45.305 38.366 5.5");
}

</style>
