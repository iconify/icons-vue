<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jg_a1sh_j"/><path class="rb1gwpmxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anomaly-detect" /></template>
<style>
.jg_a1sh_j {
  d: path("M3.5 3v17.5h9.1");
}

.rb1gwpmxc {
  d: path("m6.5 14.5l2-2.5l2 1.5l2-10l2 7l2.5-2l3 1M14.25 18c1.25-2.25 6.25-2.25 7.5 0c-1.25 2.25-6.25 2.25-7.5 0ZM18 18h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
