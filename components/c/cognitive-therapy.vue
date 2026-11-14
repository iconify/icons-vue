<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wn1s-hm2r"/><path class="nu55_m0_f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cognitive-therapy" /></template>
<style>
.nu55_m0_f {
  d: path("M5.75 16.5c2.5-1 5 .25 7.5-1.25m-.75-6.5c-.75 1.5.5 2.75 0 4.5m3 4.25c1-.75 2.25-.5 2.75-1.75M5.5 4.5h13M3 2.25h2.5v4.5H3Zm15.5 0H21v4.5h-2.5ZM8.5 9.5l-.5-5M16 9l.25-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wn1s-hm2r {
  d: path("M7.75 10.75c.5-1.75 2.25-2.5 4-2c1-1 3.5-.75 4.25.5c2 0 3.25 1.5 3 3.25c1.25 1 1.25 3.25.25 4.25a2.652 2.652 0 0 1-3 3c-.75 1.25-3 1.75-4.25.75c-1.5 1-3.5.5-4.25-.75c-2 .25-3.5-1.25-3-3c-1-1-1-3.25.25-4c0-1.5 1.25-2.5 2.75-2Z");
}

</style>
