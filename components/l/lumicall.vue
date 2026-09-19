<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eo-bq3b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lumicall" /></template>
<style>
.eo-bq3b-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.007 10.071L16.293 4.5l15.6 26l4.643-2.786l4.457 7.429L27.064 43.5Z");
}

</style>
