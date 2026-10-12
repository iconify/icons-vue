<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1efkccos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lota-sharp" /></template>
<style>
.y1efkccos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5h7.5l-1 3.5c3.25 1 5 3.75 5 7c0 4.25-3.25 7.25-7.75 7.25S4 18.25 4 14c0-3.25 1.75-6 5-7ZM6 12h11.5m.75.75l3-3.25");
}

</style>
