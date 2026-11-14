<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b_87fby_x"/><path class="r_avhhbyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blister" /></template>
<style>
.b_87fby_x {
  d: path("M2.5 13.5H7c0-9 10-9 10 0h4.5M5 17.5h14");
}

.r_avhhbyl {
  d: path("M10.5 11.5c0-1 .5-1.75 1.5-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
