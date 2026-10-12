<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbfmjzb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:booster-landing-sharp" /></template>
<style>
.vbfmjzb6d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.75h4.5v12h-4.5zm0 2.25h-1.5m6 0h1.5m-6 6.5l-3.25 5m7.75-5l3.25 5M3.75 21.25h16.5M12 14.75c1.75 1.5 2 3 0 4.75c-2-1.75-1.75-3.25 0-4.75Z");
}

</style>
