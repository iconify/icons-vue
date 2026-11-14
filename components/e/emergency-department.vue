<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="shwf3pt4m"/><path class="hj28stbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-department" /></template>
<style>
.hj28stbge {
  d: path("M9.5 21.5V16h5v5.5");
}

.shwf3pt4m {
  d: path("M3 9.5h18v12H3ZM10 8V6c0-1.1.9-2 2-2s2 .9 2 2v2M9 8h6M7.5 4.5l1 1m8-1l-1 1m-10 8h13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
