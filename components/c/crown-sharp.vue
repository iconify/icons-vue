<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-f9nlbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crown-sharp" /></template>
<style>
.i-f9nlbfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.31 7.75l3.13 2.75l.56.5l.43-.62l3.14-4.51l.43-.62l.43.62l3.14 4.51l.43.62l.56-.5l3.13-2.75l.56-.5l-.11.74l-1.28 8.52l-.11.74H5.25l-.11-.74l-1.28-8.52l-.11-.74zm1.44 12.5h12.5");
}

</style>
