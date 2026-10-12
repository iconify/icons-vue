<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfhv63bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-timeline-sharp" /></template>
<style>
.tfhv63bey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.75h18.5m-15.75 0v2.5m6.5-2.5v2.5m6.5-2.5v2.5M2.75 4h6v3.5h-6zm11 0h7.5v3.5h-7.5zm-9 6.5h4V14h-4zm9 0h4.75V14h-4.75zm-2.5-7.75v13.5");
}

</style>
