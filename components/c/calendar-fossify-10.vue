<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i5fjrmbsi"/><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-10" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.i5fjrmbsi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.176 33.062c0 2.074 1.66 3.733 3.733 3.733s3.595-1.659 3.595-3.733v-3.733c0-2.074-1.659-3.734-3.595-3.734s-3.733 1.66-3.733 3.734zm-7.68-5.927l2.8-1.54m0 0v11.2");
}

</style>
