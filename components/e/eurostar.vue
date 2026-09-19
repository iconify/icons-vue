<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aeiodp_gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eurostar" /></template>
<style>
.aeiodp_gu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 39V9m13.595 21.339l-27.19-12.678m0 12.679l33.083-15.427l.002-.001C40.066 7.58 32.626 2.5 24 2.5C12.126 2.5 2.5 12.126 2.5 24S12.126 45.5 24 45.5S45.5 35.874 45.5 24");
}

</style>
