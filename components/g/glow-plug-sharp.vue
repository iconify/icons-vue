<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i95b7tbzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:glow-plug-sharp" /></template>
<style>
.i95b7tbzf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.5v11m18.5-11v11m-18.5-2.25h4.54m9.42 0h4.54m-13.96 0c1.96 0 3.77-1.55 4.03-3.25S10.3 8.75 8.86 8.75S6.13 10.3 6.39 12c.27 1.7 2.08 3.25 4.04 3.25S14.2 13.7 14.46 12c.27-1.7-1.02-3.25-2.46-3.25S9.27 10.3 9.54 12c.26 1.7 2.07 3.25 4.03 3.25s3.77-1.55 4.04-3.25c.26-1.7-1.03-3.25-2.47-3.25S12.42 10.3 12.68 12s2.07 3.25 4.03 3.25");
}

</style>
