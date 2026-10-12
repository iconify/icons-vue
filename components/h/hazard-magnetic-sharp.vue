<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uu0a_bbmx"/><path class="q7wpfibzh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hazard-magnetic-sharp" /></template>
<style>
.q7wpfibzh {
  d: path("M9.75 11v2.5a2.25 2.25 0 0 0 4.5 0V11m-4.5 1.5H11m2 0h1.25");
}

.uu0a_bbmx {
  d: path("m12.98 4.99l7.29 13.02l.98 1.74H2.75l.98-1.74l7.29-13.02l.98-1.74z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
