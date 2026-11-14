<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vhnhndx-r"/><path class="cb_kavbxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apple" /></template>
<style>
.cb_kavbxs {
  d: path("M12 8.5c0-2.5 1-4.5 3-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhnhndx-r {
  d: path("M12 8.5c-2.5-2-6.5-.5-6.5 4C5.5 16.75 8 20 10 20c1 0 1.5-.5 2-.5s1 .5 2 .5c2 0 4.5-3.25 4.5-7.5c0-4.5-4-6-6.5-4Z");
}

</style>
