<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="v0m8db-_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:contract-edit-sharp" /></template>
<style>
.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.v0m8db-_q {
  d: path("M13.75 2.75v5.5h5.5m-10.5 3h6.5m-6.5 3h6.5M8.75 18c.75-1.5 1.5-1.5 1.75 0s1.25-1.5 2 0h2.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
