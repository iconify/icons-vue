<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qic70er6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hydroponics-sharp" /></template>
<style>
.qic70er6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7.75q.38-2.91-2.5-3.5q-.38 2.91 2.5 3.5Zm0 0q2.88-.59 2.5-3.5q-2.88.59-2.5 3.5Zm9 0q.38-2.91-2.5-3.5q-.38 2.91 2.5 3.5Zm0 0q2.88-.59 2.5-3.5q-2.88.59-2.5 3.5Zm-9 0v3m9-3v3m-13.75 0h18.5v4.5H2.75zm4.75 4.5v4m0-2l-1.5 2m6-4v6m0-3.5l1.5 2m3-4.5v4m0-2l1.5 2");
}

</style>
