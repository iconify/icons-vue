<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s322sv6dy"/><path class="jxdm_fbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:face-scan-3d" /></template>
<style>
.jxdm_fbqs {
  d: path("M14.5 16.25L18 18l3.5-1.75M18 18v3.75");
}

.s322sv6dy {
  d: path("M3 8V5a2 2 0 0 1 2-2h3m8 0h3a2 2 0 0 1 2 2v3M3 16v3a2 2 0 0 0 2 2h3M9.25 9a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM7.5 19c0-2.911 1.883-4.409 4.278-4.496M18 14.5l3.5 1.75V20L18 21.75L14.5 20v-3.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
