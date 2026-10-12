<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gweqoyclt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:detour-sharp" /></template>
<style>
.gweqoyclt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25v-4.5m0 2.75c-3.5 0-6.5-2.25-6.5-6s3-6 6.5-6V2.75M10.25 4.5L12 2.75l1.75 1.75m-3 6.75l2.5 2.5m0-2.5l-2.5 2.5");
}

</style>
