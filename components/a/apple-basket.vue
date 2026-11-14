<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lsm99tb0g"/><path class="pcw63tb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:apple-basket" /></template>
<style>
.lsm99tb0g {
  d: path("M2.5 12h19v2.75h-19ZM4 14.75l1.75 5.75h12.5L20 14.75M10.25 12a3.5 3.5 0 1 1 3.5 0");
}

.pcw63tb9c {
  d: path("M3 12a3.5 3.5 0 0 1 5.5-2.75M21 12a3.5 3.5 0 0 0-5.5-2.75M12 5.5Q12.25 4 13.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
