<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl0t7jbrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bow-arrow-sharp" /></template>
<style>
.kl0t7jbrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9.5q11 0 11 11m-11-11l11 11M6 18L17.5 6.5M6 18H3.5M6 18v2.5M20.54 3.81l-1.48 3.98l-.21.56l-.42-.42l-2.36-2.36l-.42-.42l.56-.21l3.98-1.48l.56-.21z");
}

</style>
