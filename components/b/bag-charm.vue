<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kb8o71fvl"/><path class="jh--vwb6r"/><path class="cnib-t67u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bag-charm" /></template>
<style>
.cnib-t67u {
  d: path("M12 17c-1.5 0-2 2.5-2 4.5h4c0-2-.5-4.5-2-4.5Z");
}

.jh--vwb6r {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.kb8o71fvl {
  d: path("M8.5 4.5a3.5 2.5 0 1 0 7 0a3.5 2.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
