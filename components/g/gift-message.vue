<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aw-g4rp-v"/><path class="hvozhac_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-message" /></template>
<style>
.aw-g4rp-v {
  d: path("M12 5.5H4.5A1.5 1.5 0 0 0 3 7v12.5A1.5 1.5 0 0 0 4.5 21H12Zm0 0l9-3v14L12 21");
}

.hvozhac_b {
  d: path("M7.5 15.75S5 14 5 12.5c0-1 .75-1.5 1.5-1.5c.5 0 1 .5 1 1c0-.5.5-1 1-1c.75 0 1.5.5 1.5 1.5c0 1.5-2.5 3.25-2.5 3.25Zm7.25-7.5L18.25 7m-3.5 4.5l3.5-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
