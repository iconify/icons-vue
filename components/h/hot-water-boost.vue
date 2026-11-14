<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlfn4vdtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hot-water-boost" /></template>
<style>
.xlfn4vdtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.585 11.867C16.08 7.58 11 2.5 11 2.5S4 9.5 4 14q0 .292.024.582q.025.291.073.579q.048.287.12.57q.072.282.168.558q.095.276.213.542q.118.267.258.523t.3.5q.161.243.341.473t.379.442q.199.214.415.41t.447.374t.477.335t.503.295t.525.251t.545.207t.56.161M19 14.5l-3.5 3.75h5l-3.5 3.5");
}

</style>
