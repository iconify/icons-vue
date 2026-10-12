<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xlusco2lt"/><path class="mtohnxbsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hard-drive-download-sharp" /></template>
<style>
.mtohnxbsi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xlusco2lt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25h18.5v11.5H2.75zM6.25 12h6");
}

</style>
