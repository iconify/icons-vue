<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ln4wn4b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bookmory" /></template>
<style>
.ln4wn4b6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.5h27.75a9.25 9.25 0 0 0 0-18.5a9.25 9.25 0 0 0 0-18.5H5.5m0 18.5h27.75M5.5 33.25h27.75M5.5 14.75h27.75");
}

</style>
