<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lg1f68-5k"/><path class="gd7s1abys"/><path class="vfp392enh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flower-bee" /></template>
<style>
.gd7s1abys {
  fill: currentColor;
  d: path("M8 14h.01");
}

.lg1f68-5k {
  d: path("M6 11.25a2.25 2.25 0 1 1 4 0A2.25 2.25 0 1 1 11.25 15A2.25 2.25 0 1 1 8 17.5A2.25 2.25 0 1 1 4.75 15A2.25 2.25 0 1 1 6 11.25Zm2 6.25v4m5.5-12.75a4 2.25 0 1 0 8 0a4 2.25 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfp392enh {
  d: path("M16 6.75v4m3-4v4M17.5 6.5C15.5 6.5 13 5 14 3c1-1.25 3 .5 3.5 3.5Zm0 0C18 3.5 20 1.75 21 3c1 2-1.5 3.5-3.5 3.5Z");
}

</style>
