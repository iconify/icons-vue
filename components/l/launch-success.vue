<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbp6svnmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:launch-success" /></template>
<style>
.sbp6svnmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5c2.75 2 3.5 4.75 3.5 8v5h-7v-5c0-3.25.75-6 3.5-8ZM5.5 11l-2 2v2.5h2m7-4.5l2 2v1.272M13.328 15.5H12.5m-4.5 2l1 2l1-2M3 21h10m1.75-3l2 2L21 15.75");
}

</style>
