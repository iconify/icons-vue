<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tm9b659pt"/><path class="pxb63-6tb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:judges-scorecard" /></template>
<style>
.pxb63-6tb {
  d: path("M12 4.75L13.25 8l3.5.25L14 10.5l1 3.25l-3-2l-3 2l1-3.25l-2.75-2.25l3.5-.25Z");
}

.tm9b659pt {
  d: path("M3.5 2h17v15h-17Zm7 15v4.5h3V17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
