<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x4oer2_3y"/><g class="y9tr6bcfx"><path class="wqlddb-sl"/><path class="r5qpqxb_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adaptive-pack" /></template>
<style>
.r5qpqxb_u {
  d: path("M24.032 17.104zc7.67 0 13.887 6.218 13.887 13.887c0 1.09-.884 1.975-1.975 1.975H12.056a1.975 1.975 0 0 1-1.975-1.975c0-7.67 6.217-13.887 13.887-13.887zm-11.976-2.07l3.949 4.634m20.035-4.634l-3.934 4.634");
}

.wqlddb-sl {
  d: path("M18.394 29.096a1.959 1.959 0 1 1 1.943-1.879a1.943 1.943 0 0 1-1.943 1.88m11.339-.001a1.959 1.959 0 1 1 1.943-1.879a1.943 1.943 0 0 1-1.943 1.88");
}

.x4oer2_3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 2.98C11.24 4.74 4.74 11.24 2.98 19.5m42.04 0C43.26 11.24 36.76 4.74 28.5 2.98m0 42.04c8.26-1.76 14.76-8.26 16.52-16.52m-42.04 0c1.76 8.26 8.26 14.76 16.52 16.52");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
