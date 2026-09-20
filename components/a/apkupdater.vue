<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ibdit5upg"/><path class="mm_uz2bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apkupdater" /></template>
<style>
.ibdit5upg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39 13.71l2.59-2.55a3 3 0 0 0-4.28-4.27l-2.55 2.6a18.44 18.44 0 0 0-21.52 0l-2.57-2.57A3.14 3.14 0 0 0 8.5 6a3 3 0 0 0-2.12.88a3 3 0 0 0 0 4.26L9 13.7a18.55 18.55 0 0 0-3.5 10.81v15.57a2 2 0 0 0 2 2h33.1a2 2 0 0 0 2-2V24.51a18.5 18.5 0 0 0-3.6-10.8m-25.86 7a3.07 3.07 0 1 1 3.07 3.07a3.08 3.08 0 0 1-3.07-3.07M24 40.05a7 7 0 1 1 7-7a7 7 0 0 1-7 7m7.79-16.29a3.07 3.07 0 1 1 3.06-3.07a3.07 3.07 0 0 1-3.06 3.07M24 28.58v8.52");
}

.mm_uz2bma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.09 34.06L24 37.29l2.91-3.23");
}

</style>
