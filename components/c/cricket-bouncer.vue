<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gnas-eb6z"/><path class="ywk3cdbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cricket-bouncer" /></template>
<style>
.gnas-eb6z {
  d: path("M11 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM3 7l4.5 11.75q2-4.25 3.25-5M2.5 21.5h10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ywk3cdbkf {
  d: path("M20.5 5.25A8 8 0 0 0 13.75 12m4.5-9a10 10 0 0 0-6.75 6.75");
}

</style>
