<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="csa4-bk9e"/><path class="n0mi9wg2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gosling" /></template>
<style>
.csa4-bk9e {
  d: path("M6.25 7.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.n0mi9wg2i {
  d: path("M7.5 10.5c-3 3.5-1.5 10 5 10c6 0 9-3.5 8.5-8c-2 1.5-5.5 1-8.25-2.25M6.5 6.5L4 7.5l2.5 1m4.25-2h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
