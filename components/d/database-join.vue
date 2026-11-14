<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="amfmfs6ya"/><path class="yaq__qb3d"/><path class="e_gp7hbps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-join" /></template>
<style>
.amfmfs6ya {
  d: path("M2.5 2.5H14V14H2.5Z");
}

.e_gp7hbps {
  fill: currentColor;
  d: path("M10 10h4v4h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yaq__qb3d {
  d: path("M10 10h11.5v11.5H10ZM2.5 6.25H14M14 14h7.5");
}

</style>
