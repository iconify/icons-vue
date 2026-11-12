<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><path class="tw30_ubet"/><path class="yic1xvbbc"/><path class="gcqwp0nsv"/><path class="w09pzi5lx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:black-hole-3-broken" /></template>
<style>
.gcqwp0nsv {
  d: path("M10 12.3115C10 9.53259 13.7068 8.42171 17 9.28791M20 10.8222C21.1941 11.856 22 13.342 22 15.3115");
}

.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tw30_ubet {
  d: path("M12 10C17 10 16.6 22 9 22");
}

.w09pzi5lx {
  d: path("M3.5 13.0041C2.58642 12.0083 2 10.6801 2 9M14 12C14 14.7789 10.2932 15.8898 7 15.0236");
}

.yic1xvbbc {
  d: path("M12.3115 14C7.31152 14 7.71152 2 15.3115 2");
}

</style>
