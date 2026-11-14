<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lu09fy6wb"/><path class="i9oaqwo_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:call-in-show" /></template>
<style>
.i9oaqwo_w {
  d: path("M3 9.5q0 .16.008.319t.023.318t.039.317t.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285t.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157q.141.076.285.144t.292.129t.297.115q.15.054.303.1t.308.085t.311.07t.314.055t.317.039t.318.023T9.5 16q.487 0 .969-.073q.482-.072.948-.216t.904-.355q.439-.212.842-.486m1.677-1.663q.281-.406.498-.85q.218-.444.365-.915q.148-.471.222-.96Q16 9.994 16 9.5M9.5 16v5.5m-3 0h6M16 16h2l1 2.25l-1.25 1c.5 1 1 1.5 2 2l1-1.25l1.25.75V22h-1c-2.75 0-5-2.25-5-5Z");
}

.lu09fy6wb {
  d: path("M7.5 2.5h4A1.5 1.5 0 0 1 13 4v7.5a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 6 11.5V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
