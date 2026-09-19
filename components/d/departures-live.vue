<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oy48ofr2k"/><path class="h3yx0d0iu"/><path class="sjrq6u0ge"/><circle class="p3zrrizbl"/><path class="xqbu7bomb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:departures-live" /></template>
<style>
.h3yx0d0iu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.822 37.624h3.015v1.949c0 .589-.478 1.067-1.066 1.067h-.882a1.067 1.067 0 0 1-1.067-1.067zm12.031 0h3.015v1.949c0 .589-.478 1.067-1.067 1.067h-.882a1.067 1.067 0 0 1-1.066-1.067zm1.966-15.231H25.912a.57.57 0 0 0-.567.54l-.235 4.86a.57.57 0 0 0 .567.595h13.376a.57.57 0 0 0 .567-.595l-.234-4.86a.57.57 0 0 0-.567-.54m-17.997-8.408H9.115a.515.515 0 0 0-.515.49l-.213 4.408c-.014.294.22.54.515.54h12.133a.515.515 0 0 0 .514-.54l-.213-4.408a.515.515 0 0 0-.514-.49");
}

.oy48ofr2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.816 37.624H23.915c-.965 0-1.733-.81-1.682-1.773l.856-16.22a1.684 1.684 0 0 1 1.682-1.595H39.96c.895 0 1.634.701 1.681 1.596l.857 16.22a1.684 1.684 0 0 1-1.682 1.772M26.37 20.179h11.99m-13.754 13.43h2.448m10.838 0h2.449");
}

.p3zrrizbl {
  cx: 14.968px;
  cy: 26.399px;
  r: 2.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sjrq6u0ge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.4 32.673H9.23a5.7 5.7 0 0 0-1.269-1.282c-.96-.7-1.92-.933-2.461-1.022l.518-19.696A1.74 1.74 0 0 1 7.755 8.98H22.12c.942 0 1.712.75 1.737 1.692l.198 7.529M7.233 7.36h15.41");
}

.xqbu7bomb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.387 11.222H21.55");
}

</style>
