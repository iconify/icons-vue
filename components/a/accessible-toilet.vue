<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w6ps77_ly"/><path class="tsvp5r5pl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:accessible-toilet" /></template>
<style>
.tsvp5r5pl {
  d: path("M16.5 14.5V19h2.75L21 21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6ps77_ly {
  d: path("M3 2.5h5v8H3Zm10.696 11.677c-.813.943-1.941 1.572-3.196 1.823l.5 4H5.5l.5-4.5c-1.75-1-3-2.75-3-5h12q0 .633-.114 1.204M14 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
