<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tndv68f6j"/><path class="r2iik92ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hak" /></template>
<style>
.r2iik92ow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.656 29.247L32.26 24l5.24-5.212M32.26 24h-1.32m-20.049 3.03l-.391 2.217m1.85-10.494l-.384 2.177m7.337-2.177l-1.851 10.494m9.222-3.51h-4.546m-1.747 3.479l5.255-10.463l1.56 10.494M14.905 23.98h3.476");
}

.tndv68f6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-6.634 13.253l-1.851 10.494");
}

</style>
