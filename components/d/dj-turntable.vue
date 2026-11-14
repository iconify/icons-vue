<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="dylwfobwz"/><path class="oc0pwc2_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dj-turntable" /></template>
<style>
.dylwfobwz {
  d: path("M5 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm5 0h.01m5.74-5.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.oc0pwc2_v {
  d: path("M17.5 8.5V13l-3.25 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
