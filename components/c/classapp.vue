<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zeg-c4fhx"/><path class="ybsuv5osr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:classapp" /></template>
<style>
.ybsuv5osr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.136v13.228c2.248-1.94 8.213-2.401 10.286-2.401V15.735c-2.073 0-8.038.461-10.286 2.401c-2.248-1.94-8.213-2.4-10.286-2.4v13.227c2.073 0 8.038.46 10.286 2.4");
}

.zeg-c4fhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.953c-10.77 0-19.5 6.842-19.5 15.283S13.23 38.52 24 38.52a24.5 24.5 0 0 0 5.585-.663l4.315 2.19l-.082-3.61c5.993-2.738 9.68-7.764 9.682-13.2c0-8.441-8.73-15.284-19.5-15.284");
}

</style>
