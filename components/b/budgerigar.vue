<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dca0lwqnc"/><path class="z1l2kj4tx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:budgerigar" /></template>
<style>
.dca0lwqnc {
  d: path("M14 3.5c1.75 0 2.5 1 2.75 2c1.75 0 2 2.5.5 3.25l-1-1c.75 2.75-.25 6-3.25 7.75L5 21l3-5c.5-4 1-8 2-10c.75-1.75 2.25-2.5 4-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1l2kj4tx {
  d: path("m13 15.5l1 2h6.5m-6.75-11h.01");
}

</style>
