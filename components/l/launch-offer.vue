<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e95b38htp"/><path class="yy-rr_bjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:launch-offer" /></template>
<style>
.e95b38htp {
  d: path("M14.939 18.811L12.5 21.25L2.75 11.5l8.75-8.75h8q.086 0 .172.008t.169.026q.085.016.167.041t.162.058t.155.074t.147.088t.138.102t.127.116q.061.06.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167q.017.084.026.169t.008.172v8l-2.493 2.493");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yy-rr_bjl {
  d: path("M15.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-6 7.5l5-5M10 10h.01M14 14h.01m4.24 1q0 3.25 3.25 3.25q-3.25 0-3.25 3.25q0-3.25-3.25-3.25q3.25 0 3.25-3.25Z");
}

</style>
