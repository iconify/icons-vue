<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dwy8zubix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aura" /></template>
<style>
.dwy8zubix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.824 7.594c2.827 2.508 13.391 25.45 13.925 27.317c.533 1.867.373 5.495.373 5.495H42.5L27.881 7.594zm2.054 32.812H5.5l5.895-13.23c1.108 3.173 4.776 11.163 6.483 13.23");
}

</style>
