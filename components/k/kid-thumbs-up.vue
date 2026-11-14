<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbu1ixbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kid-thumbs-up" /></template>
<style>
.kbu1ixbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11H8v10.5H2.5ZM8 11h2.5L12 5c.5-2.25 4-2.25 4 .5v5h3a2.5 2.5 0 0 1 2.5 2.5l-1.25 6.25a2.5 2.5 0 0 1-2.5 2.25H8Zm5 5.5h7.75");
}

</style>
