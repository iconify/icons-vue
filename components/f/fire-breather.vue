<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw_sj_bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fire-breather" /></template>
<style>
.aw_sj_bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.5v-5.25C3 15 2.5 13 2.5 11c0-3.75 2.75-6.5 6.25-6.5c3 0 5 2 5 5l1 2l-1 .25l-1.5 1l1.5 1V15c0 .75-.5 1.25-1.25 1.25H11v5.25m6-8.75q1.875-1.5 1.5-4.5c2 1.5 3 3.5 3 5.5c0 2.5-1.75 4-3.5 3.75c.75-1.5.5-3.75-1-4.75Z");
}

</style>
