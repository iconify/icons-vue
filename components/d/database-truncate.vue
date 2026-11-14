<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hktv0wmrq"/><path class="pwbyrptkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-truncate" /></template>
<style>
.hktv0wmrq {
  d: path("M4 5a8 2.5 0 1 0 16 0A8 2.5 0 1 0 4 5Z");
}

.pwbyrptkf {
  d: path("M4 5v7a8 2.5 0 0 0 16 0V5M4 15v3.75a8 2.5 0 0 0 2.25 1.75m3 .5a8 2.5 0 0 0 5.5 0m3-.5A8 2.5 0 0 0 20 18.75V15");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
