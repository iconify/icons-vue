<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qljf82c2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flud" /></template>
<style>
.qljf82c2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.66 4.5c0 4.09-13 15.8-13 25.58s7.67 13.42 13 13.42c4.77 0 13.64-2 13.64-12.62c0-11.6-13.64-18.53-13.64-26.38");
}

</style>
