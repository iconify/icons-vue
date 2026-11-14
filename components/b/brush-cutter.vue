<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nq-k7b-im"/><path class="lkj1-abuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brush-cutter" /></template>
<style>
.lkj1-abuf {
  d: path("M14 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm.5 1l-6.75 6.75m-5.432 3.311l4.243-4.243l2.121 2.121l-4.243 4.243Z");
}

.nq-k7b-im {
  d: path("m19.25 10l1.5.75l-3.75 1.5l.75 1.5l-3.75-1.5l-.75 1.5l-1.5-3.75l-1.5.75L11.75 7l-1.5-.75L14 4.75l-.75-1.5L17 4.75l.75-1.5L19.25 7l1.5-.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
