<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aopd2tfez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aeg-kitchen" /></template>
<style>
.aopd2tfez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.13 4.5v36.901a2.099 2.099 0 1 0 4.198 0V25.49h5.056zm-11.217 0v10.924M23.21 4.5v11.736a4.2 4.2 0 0 1-4.198 4.198v20.967a2.099 2.099 0 1 1-4.198 0V20.434a4.2 4.2 0 0 1-4.198-4.198V4.5");
}

</style>
