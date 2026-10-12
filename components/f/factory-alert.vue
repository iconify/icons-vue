<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l00-nmb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:factory-alert" /></template>
<style>
.l00-nmb1e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25V12.5q0-1 .83-1.55l3.59-2.4Q8 8 8 9v1.5q0 1 .83.45l3.59-2.4q.83-.55.83.45v1.5q0 1 .83.45l.59-.4Q15.5 10 15.5 9V3.75q0-1 1-1h3.75q1 0 1 1v16.5q0 1-1 1H3.75q-1 0-1-1m3.5-4h2m2.75 0h2m2.75 0h2");
}

</style>
