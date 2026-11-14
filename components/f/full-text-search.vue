<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k74i0kbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:full-text-search" /></template>
<style>
.k74i0kbev {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.25H17m-14.5 5h5.3m-5.3 5h4.9m-4.9 5H9m1-7a5 5 0 1 0 10 0a5 5 0 1 0-10 0Zm8.5 3.5l3 3");
}

</style>
