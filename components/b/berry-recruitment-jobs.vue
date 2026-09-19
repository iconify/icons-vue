<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j9mj8qb7x"/><circle class="x-wvkjb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:berry-recruitment-jobs" /></template>
<style>
.j9mj8qb7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.5 36.412V42.5h20c2.216 0 4-1.784 4-4v-29c0-2.216-1.784-4-4-4h-20v17.088a13 13 0 0 1 11-6.088c7.18 0 13 5.82 13 13s-5.914 12.998-13 12.998c-4.397 0-8.624-2.3-11-6.086M9.5 5.5c-2.216 0-4 1.784-4 4v29c0 2.216 1.784 4 4 4h5v-37z");
}

.x-wvkjb4r {
  cx: 29.5px;
  cy: 29.5px;
  r: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
