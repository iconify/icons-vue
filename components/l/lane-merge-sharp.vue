<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uu0a_bbmx"/><path class="pt2ll5v9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lane-merge-sharp" /></template>
<style>
.pt2ll5v9b {
  d: path("M13 18.25v-8.5m-3.75 8.5c0-2.5 3.75-3.5 3.75-6");
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
