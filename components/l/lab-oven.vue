<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o7y6k3b2a"/><path class="qi3xiibto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-oven" /></template>
<style>
.o7y6k3b2a {
  d: path("M3 3h18v18H3Zm0 6h18");
}

.qi3xiibto {
  d: path("M7 12h10v6H7Zm0-6h.01M11 6h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
