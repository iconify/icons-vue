<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pvi8foxke"/><path class="r0xl7acoe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:liabilities-column" /></template>
<style>
.pvi8foxke {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8M8 10h5.5");
}

.r0xl7acoe {
  fill: currentColor;
  d: path("M7.25 13.5h9.5v5.25h-9.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
