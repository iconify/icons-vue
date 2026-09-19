<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z5ejmvb0m"/><path class="rcydelkar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:http-custom" /></template>
<style>
.rcydelkar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.793 17.717l-9.826-6.037v25.157l9.826-6.061");
}

.z5ejmvb0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.123 44.5L6.75 34.25V13.898L24.123 3.5L41.25 13.898V34.25zM11.97 16.042v16.237m.038-8.119h9.246m0-13.638V37.65");
}

</style>
