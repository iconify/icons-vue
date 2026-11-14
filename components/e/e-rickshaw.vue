<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="soffigqyu"/><path class="o72eg1rcf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:e-rickshaw" /></template>
<style>
.o72eg1rcf {
  d: path("M6 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9.25 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM13 10.25l-2.5 2l3-.25l-2.5 1.75");
}

.soffigqyu {
  d: path("M3 7.5c0-3 2-5 5.5-5h7c3 0 5 2 5.5 5Zm1.5 0v9h16l-1.25-9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
