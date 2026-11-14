<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="upb4v_b1n"/><path class="l3oa26cvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-records" /></template>
<style>
.l3oa26cvh {
  d: path("m13.75 11.5l2.5-1l4.25-5l-2-1.75l-4 5Zm1.75 10c0-4.5 2-6.5 6-6.5c0 4.5-2 6.5-6 6.5Zm0 0L19 18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upb4v_b1n {
  d: path("M19.5 12.38V4C16 3.5 13 4 11 5.5C9 4 6 3.5 2.5 4v13C6 16.5 9 17 11 18.5a7.8 7.8 0 0 1 2.275-1.154M11 5.5v13M5 9h3m-3 3.5h3");
}

</style>
