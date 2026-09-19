<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="guy77pi4w"/><path class="giaok4w-f"/><path class="ywnj6acvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-spatial-audio-off" /></template>
<style>
.giaok4w-f {
  fill: currentColor;
  d: path("M16.39 15.56C14.71 14.7 12.53 14 10 14s-4.71.7-6.39 1.56A2.97 2.97 0 0 0 2 18.22V21h16v-2.78c0-1.12-.61-2.15-1.61-2.66M20.36 1l-1.41 1.41a7.007 7.007 0 0 1 0 9.9l1.41 1.41a8.98 8.98 0 0 0 0-12.72");
}

.guy77pi4w {
  cx: 10px;
  cy: 9px;
  r: 4px;
  fill: currentColor;
}

.ywnj6acvp {
  fill: currentColor;
  d: path("M17.54 10.9a5.003 5.003 0 0 0 0-7.07l-1.41 1.41a3 3 0 0 1 0 4.24z");
}

</style>
