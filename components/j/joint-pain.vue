<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9ogerg7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:joint-pain" /></template>
<style>
.d9ogerg7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5v6c-1.5 1-1.25 3 .75 3.25h4.25c1.75-.25 2-2.25.5-3.25v-6m-5 19V16c-1.5-1-1.25-2 .25-2h4.25c1.5 0 1.75 1 .25 2v5.5M16 12.75h5.5m-6-4.25l4-3.5m-4 12l4 3.5");
}

</style>
