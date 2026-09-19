<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dndr4fy-b"/><path class="pt_8wqb0q"/><path class="z4_1cwb6x"/><path class="e6j0qdbqo"/><circle class="ey6j-vbhq"/><circle class="mkkxji67d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:happychick" /></template>
<style>
.dndr4fy-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.328 18.832c6.534-.093 6.544 9.961 0 9.87c-6.558.091-6.548-9.965 0-9.87m-13.22 13.47c1.182 2.357 4.456 4.647 4.98 1.01c.07-.31.14-.41.34-.29c1.542 1.376 2.425-1.384 1.76-2.56");
}

.e6j0qdbqo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.698 35.942c-4.635 1.404.018 5.218 4.682 4.357m20.178-10.957c.32-2.07-.72-2.28-2.31-1.39z");
}

.ey6j-vbhq {
  cx: 27.489px;
  cy: 23.962px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mkkxji67d {
  cx: 37.678px;
  cy: 24.413px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pt_8wqb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.524 24.88l-1.576 1.312l-8.37-5.07c-1.003 1.096-3.478 3.738-4.62 4.63c-3.02-9.975 6.25-19.4 16.02-19.81c9.726-.408 20.783 7.736 18.22 18.16c-.764-.887-2.3-2.679-3.06-3.57l-4.41 3.68l-2.496-1");
}

.z4_1cwb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.683 24.159c-1.56 9.852 1.868 17.593 12.716 17.593c14.294 0 22.894-4.818 18.51-19.15");
}

</style>
