<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eq71igysm"/><path class="g4b9w7b2c"/><path class="ipn28vbme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brain-bleed" /></template>
<style>
.eq71igysm {
  d: path("M14.759 13.514q-.36.042-.759-.014c-.75 1.25-2.75 1.5-4 .75c-1.25.75-3.25.5-4-.75c-1.75.25-3-1.25-2.75-2.75c-1-1-1-3 .25-3.75c0-1.5 1.25-2.25 2.5-2c.5-1.5 2.25-2.25 4-1.75c1-1 3-.75 4 .5c1.75 0 3 1.25 2.75 3c1.25 1 1.25 3 .25 4q0 .087-.004.171M12.25 14.75l.268 1.476");
}

.g4b9w7b2c {
  d: path("M4.25 10.5c2.25-1 4.75.25 7-1.25M10.5 3c-.5 1.75.5 3 0 4.5m3 4c.75-.75 2-.5 2.5-1.5m2 4c1.75 2 3 3.5 3 5c0 1.6-1.4 2.75-3 2.75S15 20.6 15 19c0-1.5 1.25-3 3-5Z");
}

.ipn28vbme {
  fill: currentColor;
  d: path("M15 19h6c0 1.6-1.4 2.75-3 2.75S15 20.6 15 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
