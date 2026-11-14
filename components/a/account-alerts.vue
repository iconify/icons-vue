<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ipof0itfh"/><path class="crc0cf2do"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-alerts" /></template>
<style>
.crc0cf2do {
  d: path("M13.75 9.25C13.5 8.5 12.9 8 12 8c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M12 7.25V8m0 6v1.25");
}

.ipof0itfh {
  d: path("M6 10.5a6 6 0 0 1 12 0v4l1.5 2.25c.35.5.1 1.25-.5 1.25H5c-.6 0-.85-.75-.5-1.25L6 14.5Zm6-8v2M10 21h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
