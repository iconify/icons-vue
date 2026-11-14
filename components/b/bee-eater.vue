<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w6c7evf3v"/><path class="y1kbc1h2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bee-eater" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6c7evf3v {
  d: path("M7 6.5c1-2.5 4.5-3 6.5-.5l7 3.5l-7 1.5C11 12.5 8 11.5 7 9ZM7 7q-2.25 1-4 4m7-3.75h.01m5.24 11.5a3 2.25 0 1 0 6 0a3 2.25 0 1 0-6 0Zm3-2.25V21");
}

.y1kbc1h2u {
  d: path("M18.25 16.5c-1.25-3-3.5-1.75-2 .5m2-.5c1.25-3 3.5-1.75 2 .5");
}

</style>
