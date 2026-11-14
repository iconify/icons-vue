<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkpmmcceb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-notifications" /></template>
<style>
.dkpmmcceb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.151 20.5H3.5c-.6 0-1-.4-1-1c0-3.25 3-5.5 7-5.5q.98.002 1.867.174M5.75 6.75a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm6.5 12h9c-1-1-1.25-2-1.25-3.25a3 3 0 0 0-6 0c0 1.25-.25 2.25-1.25 3.25Zm4.75-7.5v1.25m0 8.5h.01");
}

</style>
