<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="scohw9bdu"/><path class="kedl3gynz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:assist-pass" /></template>
<style>
.kedl3gynz {
  d: path("M15.75 12.75L18 10.5l2.25 2.25");
}

.scohw9bdu {
  d: path("M2.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM16 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-5.75 13.5q7.5 0 7.75-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
