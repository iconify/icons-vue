<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hv-2rdbkh"/><path class="yuqe16b_o"/><path class="jsr7bxjbx"/><path class="k-ox03dns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-rounded-symbol-for-shou" /></template>
<style>
.hv-2rdbkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.018 24h19.964m-19.196-3.84h18.428m-9.214 0V24m-11.134-7.679h22.268A13.8 13.8 0 0 1 37.822 24h3.839a17.7 17.7 0 0 0-1.92-7.679m-26.875 0A13.8 13.8 0 0 0 10.18 24H6.34a17.7 17.7 0 0 1 1.92-7.679M7.107 28.607h33.786a17.66 17.66 0 0 1-14.59 13.054M7.107 28.607a17.66 17.66 0 0 0 14.59 13.054");
}

.jsr7bxjbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.321 12.482a13.82 13.82 0 0 1 15.358 0M24 6.34v6.142");
}

.k-ox03dns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 24c0 11.874 9.626 21.5 21.5 21.5S45.5 35.874 45.5 24S35.874 2.5 24 2.5S2.5 12.126 2.5 24");
}

.yuqe16b_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.25 32.446h21.5a17.66 17.66 0 0 1-8.446 5.222M13.25 32.446a17.66 17.66 0 0 0 8.446 5.222M24 28.607v3.84M10.563 12.482c6.329-7.421 17.476-8.306 24.897-1.977a18 18 0 0 1 1.977 1.977");
}

</style>
