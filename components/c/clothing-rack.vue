<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hjiokve4n"/><path class="grygxjbqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clothing-rack" /></template>
<style>
.grygxjbqf {
  d: path("M7.75 4.5v2l2.5 2.25v7.75h-5V8.75l2.5-2.25m8.5-2v2l2.25 2l.25 8.5h-5L14 8.5l2.25-2");
}

.hjiokve4n {
  d: path("M2.5 21.5v-17h19v17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
