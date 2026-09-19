<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="agg9esbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:liberapay" /></template>
<style>
.agg9esbvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.033 4.5c-1.366 5.694-4.736 20.82-5.306 23.384c-.484 2.181-1.179 6.511 2.872 7.342c4.252.872 21.277 3.932 23.82-9.785c2.306-12.447-13.625-9.5-13.625-9.5S18.281 38.94 17.41 43.5");
}

</style>
