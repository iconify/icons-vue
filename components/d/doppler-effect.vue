<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxzbs593p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doppler-effect" /></template>
<style>
.gxzbs593p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 12h.01M14 9.25a3.5 3.5 0 0 1 0 5.5m-4 0a3.5 3.5 0 0 1 0-5.5m6.5-2.75a8.5 8.5 0 0 1 0 11M3.5 16a8.5 8.5 0 0 1 0-8m16.75-1.75a13.5 13.5 0 0 1 0 11.5");
}

</style>
