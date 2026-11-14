<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tz5ne2s-t"/><path class="ms3zvac3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:centrifugation" /></template>
<style>
.ms3zvac3o {
  d: path("m10 2.25l2 2l-2 2m-2 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm4 0h.01");
}

.tz5ne2s-t {
  d: path("M19.361 8.5A8.5 8.5 0 1 1 12 4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
