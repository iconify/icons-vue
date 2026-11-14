<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dov8ejbyu"/><path class="a24037bmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:creator-badge" /></template>
<style>
.a24037bmy {
  d: path("m9 14.5l-1.5 6l2.25-1L11 21l1-5.75L13 21l1.25-1.5l2.25 1l-1.5-6m-3-9l.75 2.25l2.5.25l-1.75 1.5l.5 2.25l-2-1.25l-2 1.25l.5-2.25L8.75 8l2.5-.25Z");
}

.dov8ejbyu {
  d: path("M5.75 9a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
