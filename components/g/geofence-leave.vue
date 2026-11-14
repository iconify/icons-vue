<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b3rlp-kbw"/><path class="jgay5wdab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:geofence-leave" /></template>
<style>
.b3rlp-kbw {
  d: path("M16.495 15.75a7.5 7.5 0 1 1 0-7.5");
}

.jgay5wdab {
  d: path("M10 15.5s-2.5-2-2.5-4.25a2.5 2.5 0 0 1 5 0c0 2.25-2.5 4.25-2.5 4.25Zm5-3.5h6.5m-2-2l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
