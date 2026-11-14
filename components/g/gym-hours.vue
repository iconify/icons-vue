<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f0zjczj9i"/><path class="gzdw1g9jz"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gym-hours" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.f0zjczj9i {
  d: path("M12.26 20H3v-9.5l8-7l8 7v1.54");
}

.gzdw1g9jz {
  d: path("M7.5 20v-4.5h4V20m3.25-2a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
