<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vg1naz58m"/><path class="cz8l_fbbq"/><path class="c5qpsnbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-phone" /></template>
<style>
.c5qpsnbev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.768 7.185c-.346 4.964 4.366 12.753 4.366 12.753m-.433.256c.882 2.244 2.474 5.204 4.08 7.454s3.884 4.72 5.72 6.284");
}

.cz8l_fbbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.187 33.064c-7.572-10.617-5.778-22.056.337-26.418a33 33 0 0 1 2.813-1.787a2.73 2.73 0 0 1 3.805 1.177l3.483 7.15a2.73 2.73 0 0 1-1.065 3.545l-8.772 5.184s.965 3.605 4.003 7.865c3.04 4.26 6.133 6.346 6.133 6.346l7.758-6.606a2.73 2.73 0 0 1 3.7.148l5.625 5.621a2.73 2.73 0 0 1-.126 3.98a33 33 0 0 1-2.605 2.078C31.16 45.71 19.76 43.68 12.187 33.064");
}

.vg1naz58m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.52 41.887c-4.807-1.289-10.637-8.28-10.637-8.28");
}

</style>
