<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r6-lf0_5r"/><path class="srd_ehm6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ankle-boot" /></template>
<style>
.r6-lf0_5r {
  d: path("M4.25 4.5h6l.5 5l6 2.25C19 12.5 20 13.75 20 16H4.25Zm0 11.5v3.5h3.5V16");
}

.srd_ehm6l {
  d: path("M13.75 10.75c1 1.75 1.25 3.5 1 5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
