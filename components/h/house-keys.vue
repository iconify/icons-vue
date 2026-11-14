<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bwu5cabvn"/><path class="butkbacbm"/><path class="hq7ssstli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:house-keys" /></template>
<style>
.butkbacbm {
  d: path("M9.5 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h8m-3 0v2m2.5-2v2");
}

.bwu5cabvn {
  d: path("M3 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-.5 9L5 12.5L7.5 15v6h-5v-6m3-5.75L5 12.5");
}

.hq7ssstli {
  d: path("M8.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 11l7 7m-2.75-2.75L15 16.5m4 1.5l-1.25 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
