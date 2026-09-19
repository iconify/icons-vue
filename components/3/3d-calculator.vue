<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="elessqhsd"/><path class="b2w_03bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3d-calculator" /></template>
<style>
.b2w_03bpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.52 41.268L4.5 35.058L21.897 6.732");
}

.elessqhsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.52 41.268l4.377-34.536L43.5 36.722Z");
}

</style>
