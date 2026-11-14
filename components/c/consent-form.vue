<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="imi1lwbqa"/><path class="aaizh6pml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consent-form" /></template>
<style>
.aaizh6pml {
  d: path("M7.5 17.5c1-2.5 2.25-2.5 2.5-.25c.25 1.75 1.5 1.5 2-.5c.5-1.25 1.5-.75 1.75.5h2.75");
}

.imi1lwbqa {
  d: path("M4.5 2.5h15v19h-15Zm3.5 4h8M8 10h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
