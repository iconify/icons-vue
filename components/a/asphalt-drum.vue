<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob9bxjb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:asphalt-drum" /></template>
<style>
.ob9bxjb5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 21.5h-10v-19h13V11m-13-3.5h13m-13 5h12m3 .75c.5 2 3 3 3 5.25a3 3 0 0 1-6 0c0-1.5 1-2.5 1.5-3.25c.25 1 .75 1.5 1.25 1.5c.25-1 0-2.5.25-3.5Z");
}

</style>
