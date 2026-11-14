<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qz9gx1bwr"/><path class="h-1xrep_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blood-bank" /></template>
<style>
.h-1xrep_v {
  d: path("M13.75 11c1.75 2 2.75 3.5 2.75 5c0 1.6-1.25 2.75-2.75 2.75S11 17.6 11 16c0-1.5 1-3 2.75-5Z");
}

.qz9gx1bwr {
  d: path("M5 2.5h14v19H5ZM5 8h14M7.75 11v3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
