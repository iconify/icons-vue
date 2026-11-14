<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iyo3ggb-l"/><path class="pv9us2wuh"/><path class="ib2j964_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:epilepsy" /></template>
<style>
.ib2j964_g {
  d: path("m6 9l1.5 1m10 3.5l1.25 1");
}

.iyo3ggb-l {
  d: path("M7 5.75c.5-2 2.75-3 4.75-2.25c1.25-1.25 4-1 5 .5c2.25 0 3.75 1.75 3.5 3.75c1.5 1.25 1.5 3.75.25 5c.25 2.25-1.5 3.75-3.5 3.5c-1 1.5-3.5 2-5 1c-1.75 1-4.25.5-5-1c-2.25.25-4-1.5-3.5-3.5C2.25 11.5 2.25 9 3.75 8c0-1.75 1.5-2.75 3.25-2.25Zm7.75 12l.75 3.75");
}

.pv9us2wuh {
  fill: currentColor;
  d: path("M13.25 5L9 11.5h3l-1.5 4.75l5-6.5h-2.75L14.5 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
