<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j3v9rw7id"/><path class="rp2bwtyrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:email-clicks-chart" /></template>
<style>
.j3v9rw7id {
  d: path("M13.7 19.5H2.5v-15h19V14m-19-6.5l9.216 5.821m3.382-1.777L21.5 7.5");
}

.rp2bwtyrz {
  d: path("m15 14.5l6 2.25L18.25 18L17 20.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
