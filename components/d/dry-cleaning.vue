<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="crk4ftegl"/><path class="t-8malb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dry-cleaning" /></template>
<style>
.crk4ftegl {
  d: path("M10 4.5a2 2 0 1 1 2 2V8m2.85 13H6.5v-7.5l-2 1l-1.5-4L8.5 8h7l5.5 2.5l-1.5 4l-2-1v.95");
}

.t-8malb6c {
  d: path("M18.5 15q.5 2.75 3.25 3.25q-2.75.5-3.25 3.25q-.5-2.75-3.25-3.25Q18 17.75 18.5 15Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
