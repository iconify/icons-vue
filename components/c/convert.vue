<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ehj214b3l"/><path class="twq03pg1b"/><path class="z9fdbpdjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:convert" /></template>
<style>
.ehj214b3l {
  d: path("M2.5 2.5H10V10H2.5ZM14 17.75a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM14 4.5h3.5a2 2 0 0 1 2 2V11");
}

.twq03pg1b {
  d: path("M17.25 8.75L19.5 11l2.25-2.25M10 19.5H6.5a2 2 0 0 1-2-2V13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z9fdbpdjf {
  d: path("M2.25 15.25L4.5 13l2.25 2.25");
}

</style>
