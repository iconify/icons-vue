<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj86jhbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-lay-log-cabin" /></template>
<style>
.rj86jhbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 5.5h19m-19 13h19m-16-16v19m13-19v19M10.75 8.25c.5 2-1.5 3-1.5 5a2.75 2.75 0 0 0 5.5 0c0-1.5-.75-2.75-1.5-3.5c-.25 1.25-.75 1.75-1.25 2c0-1.25-.25-2.5-1.25-3.5Z");
}

</style>
