<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y_ywco41j"/><path class="q8g0wo8vz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avocado-half" /></template>
<style>
.q8g0wo8vz {
  d: path("M8.75 14a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_ywco41j {
  d: path("M12 3c4.5 0 6.5 5 6.5 10c0 4.5-2.75 8-6.5 8s-6.5-3.5-6.5-8c0-5 2-10 6.5-10Z");
}

</style>
