<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uu0a_bbmx"/><path class="nlgxuddub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deer-crossing-sharp" /></template>
<style>
.nlgxuddub {
  d: path("m8.5 16.5l4.25-3l.75 1.25l-4.25 2.75Zm4.5-2.75l.5-2h1.25m-1.5-.25L12 9m.5 1l-1.5.25m2.75 1.25l-.25-1.75m0 5l1.75.75v2m-6.75-1L6.75 18");
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
