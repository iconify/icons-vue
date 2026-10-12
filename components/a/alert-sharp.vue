<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mhq1vab0a"/><path class="qs-y-_biw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alert-sharp" /></template>
<style>
.mhq1vab0a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 4.05L12 .887l1.75 3.163l7.1 12.7l1.583 2.933l-3.333.017H4.9l-3.333-.017L3.15 16.75ZM12 9v4.25");
}

.qs-y-_biw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 16.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
