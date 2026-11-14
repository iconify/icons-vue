<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2exwhc6e"/><path class="eu_odhb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cap-lamp-battery" /></template>
<style>
.eu_odhb2n {
  d: path("M18 8h.75A2.25 2.25 0 0 1 21 10.25v7.25a2.5 2.5 0 0 1-2.5 2.5H12m-.25-13L9.5 9.75h3l-2.25 2.75");
}

.o2exwhc6e {
  d: path("M3 4h15v11.5H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
