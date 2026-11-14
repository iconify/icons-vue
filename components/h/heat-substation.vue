<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vyip6-2md"/><path class="u79t6p2-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heat-substation" /></template>
<style>
.u79t6p2-n {
  d: path("M9.5 13.25C8 11.5 8 9.5 9.5 8.25c1.5 1.25 1.5 3.25 0 5Zm0 0c2.25-.5 4 .5 4.25 2.5c-1.75.75-3.5-.25-4.25-2.5Zm0 0c-.75 2.25-2.5 3.25-4.25 2.5c.25-2 2-3 4.25-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vyip6-2md {
  d: path("M2.5 5h14v16.5h-14Zm14 3.5h2.25a2.75 2.75 0 0 0 2.75-2.75V3m-5 12.5h2.25a2.75 2.75 0 0 1 2.75 2.75V21");
}

</style>
