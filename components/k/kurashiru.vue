<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u48we4muv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kurashiru" /></template>
<style>
.u48we4muv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5C13.783 5.5 5.5 13.783 5.5 24S13.783 42.5 24 42.5zM24 24a18.5 18.5 0 0 0 18.5 18.5V24zM42.5 5.5C42.5 15.717 34.217 24 24 24c0-10.217 8.283-18.5 18.5-18.5");
}

</style>
