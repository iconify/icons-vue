<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dhugf2w8a"/><path class="yfb3sr1vn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-tracking" /></template>
<style>
.dhugf2w8a {
  d: path("m2.5 12l5-6.5h14v13h-14Zm5 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yfb3sr1vn {
  d: path("m16 7.75l-4.25 4.75H15l-1.25 3.75l4.25-5h-3Z");
}

</style>
