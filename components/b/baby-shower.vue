<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uol44ybbm"/><path class="wci7kyqhy"/><path class="iy15zubxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baby-shower" /></template>
<style>
.iy15zubxm {
  d: path("m14.5 8.5l3 7l1.5-5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uol44ybbm {
  d: path("M2.5 12H14v9.5H2.5Zm5.75 0c-2.75-4.5-5.25-.5 0 0c5.25-.5 2.75-4.5 0 0m0 0v9.5m3.25-16a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.wci7kyqhy {
  d: path("M16.25 7.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

</style>
