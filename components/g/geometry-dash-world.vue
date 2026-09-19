<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="btnupwbhv"/><path class="e9i9_xkar"/><path class="xh64w_bwz"/><path class="b198xub5g"/><path class="yxa5d2bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:geometry-dash-world" /></template>
<style>
.b198xub5g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.732 31.175c-2.031 5.69 3.73 18.774 16.263 5.989");
}

.btnupwbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.785 21.622L26.38 5.028l16.594 16.594L26.38 38.215z");
}

.e9i9_xkar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.793 27.22l11.214-11.213l2.69 2.69l-11.214 11.214zm-3.829-6.854l2.776-2.776l2.776 2.776l-2.776 2.776zm5.413-5.41l2.776-2.776l2.776 2.776l-2.776 2.776z");
}

.xh64w_bwz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5C12.145 2.5 2.5 12.145 2.5 24S12.145 45.5 24 45.5S45.5 35.853 45.5 24S35.855 2.5 24 2.5");
}

.yxa5d2bmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.958 37.164h4.037v4.037");
}

</style>
