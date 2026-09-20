<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pq18nzxcr"/><circle class="eokpm4bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-analytics" /></template>
<style>
.eokpm4bio {
  cx: 10.5px;
  cy: 37.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pq18nzxcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.5 42.5za5 5 0 0 0 5-5v-27a5 5 0 0 0-10 0v27a5 5 0 0 0 5 5m-13.5 0za5 5 0 0 0 5-5v-16a5 5 0 0 0-10 0v16a5 5 0 0 0 5 5");
}

</style>
