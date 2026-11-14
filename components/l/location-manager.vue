<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cqcs9fb2c"/><path class="ovne02b_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:location-manager" /></template>
<style>
.cqcs9fb2c {
  d: path("M12 21.5c-4-4-7.5-7.5-7.5-12a7.5 7.5 0 0 1 15 0c0 4.5-3.5 8-7.5 12Z");
}

.ovne02b_y {
  d: path("M8.75 10.25L12 7l3.25 3.25v3.5h-6.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
