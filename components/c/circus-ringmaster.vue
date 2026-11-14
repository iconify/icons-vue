<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gof6h-b0r"/><path class="bcjpmjcaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:circus-ringmaster" /></template>
<style>
.bcjpmjcaf {
  d: path("M12 5.5L13 8l2.75.25L13.5 10l.75 2.75l-2.25-1.5l-2.25 1.5l.75-2.75l-2.25-1.75L11 8Z");
}

.gof6h-b0r {
  d: path("M5.5 20V4A1.5 1.5 0 0 1 7 2.5h10A1.5 1.5 0 0 1 18.5 4v16m-16 0h19m-16-4h13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
