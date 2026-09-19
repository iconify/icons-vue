<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e0cm8no2t"/><path class="j-tnh2umo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:borealis" /></template>
<style>
.e0cm8no2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.36 43.5H9.985v-39h13.373c9.961 0 16.366 10.651 8.482 18.23c10.256 6.01 7.941 20.77-8.482 20.77");
}

.j-tnh2umo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.841 22.73c-5.375.142-6.947 4.458-7.796 8.506c-1.513 7.216-10.189 2.924-14.061 10.256");
}

</style>
