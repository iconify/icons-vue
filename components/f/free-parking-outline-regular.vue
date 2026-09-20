<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gmt9v6yoq"/><path class="m2gd490yo"/><path class="kjupc8bnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:free-parking-outline-regular" /></template>
<style>
.gmt9v6yoq {
  d: path("M8 2v11");
}

.kjupc8bnz {
  d: path("M3 21v-3h3.5L9 15.5h6l2.5 2.5H21v3Z");
}

.m2gd490yo {
  d: path("M8 2h4l3.5 3.5V8L12 11.5H8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
