<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hlzdh5bnl"/><path class="l--83c_hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:giphy" /></template>
<style>
.hlzdh5bnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.582 8.774v30.452h21.37v-21.37h-8.548V8.774z");
}

.l--83c_hl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.774 43.5h30.452V13.048h-4.274V8.774h-4.274V4.5H8.774zm0-34.726h4.808M8.774 39.226h4.808m21.37 0h4.274m-4.6-21.37h4.6M26.404 8.774V4.5");
}

</style>
