<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r5au-nb0p"/><path class="nkfl_cc_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dried-flowers" /></template>
<style>
.nkfl_cc_n {
  d: path("M12 2.5V16m0-9l-5 7.5M12 7l5 7.5M10.25 9h3.5m-10 7.75a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0Zm6.5 2a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0Zm6.5-2a1.75 2.75 0 1 0 3.5 0a1.75 2.75 0 1 0-3.5 0Z");
}

.r5au-nb0p {
  fill: currentColor;
  d: path("M12 2.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
