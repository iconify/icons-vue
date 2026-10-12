<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdsltrbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dupatta" /></template>
<style>
.cdsltrbhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3h3C9 6.5 10.25 9.5 12 9.5s3-3 4.25-6.5h3a1.25 1.25 0 0 1 1.25 1.25V17a.5.5 0 0 1-.5.5h-3.25a.5.5 0 0 1-.5-.5v-6.5c-1.25 3-2.5 4.25-4.25 4.25S9 13.5 7.75 10.5V17a.5.5 0 0 1-.5.5H4a.5.5 0 0 1-.5-.5V4.25A1.25 1.25 0 0 1 4.75 3M4.5 15h2.25m10.5 0h2.25m-15 4.25V21m2.25-1.75V21m10.5-1.75V21m2.25-1.75V21");
}

</style>
