<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hr_mv3bro"/><path class="ellmzy_sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ctemplar" /></template>
<style>
.ellmzy_sn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.08 9.66C38.23 7.34 31.75 16 24 22.8C16.25 16 9.77 7.34 6.92 9.66m29.33 19.97l-10.12-8.76");
}

.hr_mv3bro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.75 29.63l10.12-8.76m3.27 20.69a43.73 43.73 0 0 0 17.32-28.69a3.3 3.3 0 0 0-1.92-3.52A41.5 41.5 0 0 0 24 6.07A41.5 41.5 0 0 0 7.46 9.35a3.3 3.3 0 0 0-1.92 3.52a43.73 43.73 0 0 0 17.32 28.69a2 2 0 0 0 2.28 0");
}

</style>
