<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="do4bm-p4w"/><path class="sj095p_cu"/><path class="gt94pljov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:episodes-two" /></template>
<style>
.do4bm-p4w {
  width: 39px;
  height: 29px;
  x: 4.5px;
  y: 11.399px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.gt94pljov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.598zA14.703 14.703 0 0 1 38.703 33.3a2.1 2.1 0 0 1-2.099 2.099H11.397a2.1 2.1 0 0 1-2.1-2.099A14.703 14.703 0 0 1 24 18.597m-12.697-2.198l4.177 4.917m21.217-4.917l-4.177 4.917");
}

.sj095p_cu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.059 11.399L7.485 7.745m5.551 3.654l3.869-6.219M24 40.4v2.42m-5.732 0h11.464M18.01 31.296a2.063 2.063 0 1 1 2.062-2.062a2.063 2.063 0 0 1-2.063 2.062m12.005 0a2.063 2.063 0 1 1 2.063-2.062a2.063 2.063 0 0 1-2.063 2.062");
}

</style>
