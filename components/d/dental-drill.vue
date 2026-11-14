<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hryv8x_dl"/><path class="jdlt1ub5z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-drill" /></template>
<style>
.hryv8x_dl {
  d: path("m6.25 7.25l12-4.5l1.5 3.5l-12 4.5Zm2.75 3v4.25m-3.5 1.25c0-1.25 1-1.75 2-1.75c.75 0 1 .5 1.5.5s.75-.5 1.5-.5c1 0 2 .5 2 1.75c0 1.75-.75 2.75-1 4.25s-1.25 1.5-1.5.25l-.5-1.75c-.25-.5-.75-.5-1 0L8 20.25C7.75 21.5 6.75 21.5 6.5 20s-1-2.5-1-4.25Z");
}

.jdlt1ub5z {
  d: path("M19 4.5c2.5 1 2.5 4.5 1.5 7c-.75 2-.75 6 1 9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
