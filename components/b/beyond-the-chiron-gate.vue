<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c4_rtnbzc"/><rect transform="rotate(45 25.77 20.39)" class="dcyjjej7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:beyond-the-chiron-gate" /></template>
<style>
.c4_rtnbzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.897 19.362l6.811 5.631m-7.199-3.385l6.811 5.631m3.7.34l6.812 5.631m-7.2-3.386l6.812 5.631m-2.191-14.548L14.79 31.37M42.122 4.038L26.286 19.875m-6.311 4.336l1.975 1.975m4.959-12.057l5.123 5.123m-5.148-1.312l1.337 1.336M14.295 30.875l.992.992a.87.87 0 0 1 0 1.23l-7.943 7.942l-2.221-2.221l7.942-7.943a.87.87 0 0 1 1.23 0");
}

.dcyjjej7t {
  width: 3.906px;
  height: 1.461px;
  x: 23.816px;
  y: 19.661px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.73px;
  ry: 0.73px;
}

</style>
