<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vc_c8_rys"/><path class="j2us7n18r"/><circle class="xcl3nsb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:inaturalist" /></template>
<style>
.j2us7n18r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.32 18S19.15 11.42 19 6.89C22.91 7 30.29 13 31.27 22.41");
}

.vc_c8_rys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.56 23.21c.88 0 3.06-8.39 12.94-5.05c-4.76 3.63-2.1 8.66-6.86 15.21A18.47 18.47 0 0 1 22 41.11a18.7 18.7 0 0 1-6.91-1.25A16 16 0 0 0 27 31.61a12.15 12.15 0 0 1-14-5.8a18 18 0 0 1 4.67-.69s-8.14-3.27-9-5.85c1.21-.95 4.94-.42 4.94-.42S5 14.1 4.5 10.86c15.25 0 25.23 12.35 26.06 12.35");
}

.xcl3nsb_k {
  cx: 37.97px;
  cy: 19.87px;
  r: 0.75px;
  fill: currentColor;
}

</style>
