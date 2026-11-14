<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ticoty_0x"/><path class="ebg7u3b9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:datacenter-map" /></template>
<style>
.ebg7u3b9w {
  d: path("M18 22c-1.75-1.75-3.25-3.25-3.25-5a3.25 3.25 0 0 1 6.5 0c0 1.75-1.5 3.25-3.25 5Zm0-5h.01");
}

.ticoty_0x {
  d: path("M12.6 19.5L9 18l-6 2.5V6l6-2.5L15 6l6-2.5v8.2M9 3.5V18m6-12v5.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
