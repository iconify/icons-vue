<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y3zy90tsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-rightwards-arrow" /></template>
<style>
.y3zy90tsp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.885 34.999L42.5 24L31.885 13.001l-2.261 2.717l6.204 6.428H5.5v3.708h30.328l-6.204 6.428z");
}

</style>
