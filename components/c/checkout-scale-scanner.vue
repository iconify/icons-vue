<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kg3u_cdpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-scale-scanner" /></template>
<style>
.kg3u_cdpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.625 18.526l.909-2A1.75 1.75 0 0 1 6.127 15.5h11.746a1.75 1.75 0 0 1 1.593 1.026l.909 2A1.75 1.75 0 0 1 18.782 21H5.218a1.75 1.75 0 0 1-1.593-2.474M12 7c-1.5-1.25-5.5-1-5.5 3.25c0 2.75 2 5.25 3.5 5.25c1 0 1.25-.5 2-.5s1 .5 2 .5c1.5 0 3.5-2.5 3.5-5.25c0-4.25-4-4.5-5.5-3.25m0 0l1-3M8 18.25h8");
}

</style>
