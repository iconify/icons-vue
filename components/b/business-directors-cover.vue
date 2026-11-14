<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf4um0t7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:business-directors-cover" /></template>
<style>
.gf4um0t7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19M4 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5.75-1a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm6.25 1a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5 14v6.5M19 14v6.5M3.25 14c0-2 1.25-3.25 2.75-3.25c1 0 1.75.5 2.25 1.25m.5 2c0-2.25 1.45-3.75 3.25-3.75s3.25 1.5 3.25 3.75m.5-2c.5-.75 1.25-1.25 2.25-1.25c1.5 0 2.75 1.25 2.75 3.25");
}

</style>
