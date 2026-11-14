<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o4q3f989j"/><path class="r-jseobla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chores" /></template>
<style>
.o4q3f989j {
  d: path("M13.142 20.5H2.5V10l6.75-6.5L16 10v4.158");
}

.r-jseobla {
  d: path("M7.5 20.5v-4H11v4m8-9.5v6m-3.25 4.5l1-4.5h4.5l.75 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
