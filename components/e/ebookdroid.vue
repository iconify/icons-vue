<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tm6zy1bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ebookdroid" /></template>
<style>
.tm6zy1bmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.48 24H6.64M24.9 9.96H4.5m20.4 23.25V10h11.58a7 7 0 1 1 0 14h0a7 7 0 1 1 0 14H4.5");
}

</style>
