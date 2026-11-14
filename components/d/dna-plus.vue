<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ua0b8kbtp"/><path class="dmbirquun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dna-plus" /></template>
<style>
.dmbirquun {
  d: path("M12 2.5c0 4-9 4-9 7.75S12 14 12 18M3.5 3.5h8M3 10.25h9M3.5 17h8m6.5-2v6m-3-3h6");
}

.ua0b8kbtp {
  d: path("M3 2.5c0 4 9 4 9 7.75S3 14 3 18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
