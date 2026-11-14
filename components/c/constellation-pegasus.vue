<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i25_gebcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:constellation-pegasus" /></template>
<style>
.i25_gebcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.988 9.845l-1.566.329m-3.249 4.862l.164.986m4.708 3.552l1.393-.146m3.452-4.498l-.282-1.879m2.223-6.882L16.5 5.5l.052-.013M2.25 11a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm9.5-2a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm1.5 10a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-9.5 1a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm15.5-15.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
