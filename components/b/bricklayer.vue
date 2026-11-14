<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgjtu1bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bricklayer" /></template>
<style>
.jgjtu1bzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8h11M6 8a4 4 0 0 1 8 0M6 8v1.5a4 4 0 0 0 8 0V8M2.5 21c0-2.75 3.25-4.5 7.5-4.5s7.5 1.75 7.5 4.5m.5-10.5h4L20 3Zm2 0v4");
}

</style>
