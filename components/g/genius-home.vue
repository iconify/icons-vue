<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jd30kzb4d"/><path class="enu2os6mz"/><path class="oy1at9bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:genius-home" /></template>
<style>
.enu2os6mz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.31 21.168a18.789 18.789 0 1 1 .07 6.088");
}

.jd30kzb4d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.689 21.164a21.5 21.5 0 1 1 .059 6.086");
}

.oy1at9bux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.501 22.598h11.728v3.253H2.501zM13.091 11.9h5.612m-7.015 2.117h8.417m-8.885 2.118h9.352m-8.896 2.118h8.418M13.09 20.37h5.612");
}

</style>
