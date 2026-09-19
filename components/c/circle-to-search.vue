<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ked93nbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:circle-to-search" /></template>
<style>
.ked93nbhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 23.96c-10.963 2.334-15.395 14.903-24.662 14.646S4.5 32.137 4.5 24.212S11.1 9.411 18.833 9.39c4.835-.012 8.135 1.763 11.444 5.192");
}

</style>
