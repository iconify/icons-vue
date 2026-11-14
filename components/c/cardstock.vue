<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lowe75bmn"/><path class="qory6h5iq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cardstock" /></template>
<style>
.lowe75bmn {
  d: path("M4 2.5h9.5l5 5v11H4Z");
}

.qory6h5iq {
  d: path("M4 18.5L6.5 21H21V10l-2.5-2.5m-5-5v5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
