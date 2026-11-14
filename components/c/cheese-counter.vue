<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y_ccnsbyl"/><path class="v_8h5b4sm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheese-counter" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_8h5b4sm {
  d: path("M7 16h10V9.5Zm7.75-2.25h.01");
}

.y_ccnsbyl {
  d: path("M3.5 19v-7.5a8.5 8.5 0 0 1 17 0V19m-18 0h19");
}

</style>
