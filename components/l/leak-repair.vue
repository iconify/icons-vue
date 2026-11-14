<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i2xksy3-k"/><path class="ym9shwbus"/><path class="wrspzobzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leak-repair" /></template>
<style>
.i2xksy3-k {
  d: path("M2.5 5H14a5 5 0 0 1 5 5v11.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrspzobzb {
  d: path("M7 3.25h2.5v8H7ZM8.25 13.5S6.5 15.75 6.5 17a1.75 1.75 0 0 0 3.5 0c0-1.25-1.75-3.5-1.75-3.5Z");
}

.ym9shwbus {
  d: path("M2.5 9.5h11a1 1 0 0 1 1 1v11");
}

</style>
