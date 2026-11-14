<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cyu6xkbbr"/><path class="p30i8cx4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:automation-add" /></template>
<style>
.cyu6xkbbr {
  d: path("M12.907 17.398L10.5 18l-1-2.5l-1.75-.5l-2 1.75l-2.5-2.5l1.75-2l-.5-1.75l-2.5-1l.75-3.25l2.75.5L6.75 5.5l-.5-2.75L9.5 2l1 2.5l1.75.5l2-1.75l2.5 2.5l-1.75 2l.5 1.75l2.5 1l-.605 2.419m-1.441.463L14.5 13.25l-1.25 1.25l.133 1.466");
}

.p30i8cx4z {
  d: path("M7.25 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm11.5 5.75v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
