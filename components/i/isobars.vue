<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j1hgu465c"/><path class="trb_6zjzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:isobars" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1hgu465c {
  d: path("M9 3c1.88-.46 4.75-.29 6.5.25s3.13 1.71 4 3c.88 1.29 1 3.04 1.25 4.75s.58 3.92.25 5.5s-1.21 3.42-2.25 4s-2.67-.54-4-.5s-2.37.88-4 .75c-1.62-.12-4.46-.21-5.75-1.5S3.13 15.21 3 13c-.12-2.21.25-5.33 1.25-7S7.13 3.46 9 3");
}

.trb_6zjzl {
  d: path("M10.5 6.5c1.38-.21 3.33.17 4.25 1s1.33 2.54 1.25 4s-.67 3.88-1.75 4.75c-1.08.88-3.37.96-4.75.5c-1.37-.46-3-1.92-3.5-3.25s-.25-3.58.5-4.75s2.63-2.04 4-2.25m-1 3v4m3-4v4m-3-2h3");
}

</style>
