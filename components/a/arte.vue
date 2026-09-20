<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="afhptwb_j"/><path class="p9z5p6uod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arte" /></template>
<style>
.afhptwb_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.48 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29.04a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.p9z5p6uod {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.468 24.326a3.72 3.72 0 0 1 3.72-3.721m-3.72 0v9.859m18.544-1.877a3.72 3.72 0 0 1-6.953-1.843v-2.418a3.72 3.72 0 1 1 7.441 0v1.209h-7.441m-3.882-7.999v11.068a1.86 1.86 0 0 0 1.86 1.86h.558m-4.371-9.859h3.906m-12.189 6.139a3.72 3.72 0 1 1-7.441 0v-2.418a3.72 3.72 0 1 1 7.441 0m0 6.138v-9.859");
}

</style>
