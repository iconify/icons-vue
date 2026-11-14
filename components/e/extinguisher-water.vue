<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hmh_3-boa"/><path class="lb2y09b6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:extinguisher-water" /></template>
<style>
.hmh_3-boa {
  d: path("M6.5 6h3v2.5A2.5 2.5 0 0 1 12 11v8a2.5 2.5 0 0 1-2.5 2.5h-3A2.5 2.5 0 0 1 4 19v-8a2.5 2.5 0 0 1 2.5-2.5Z");
}

.lb2y09b6h {
  d: path("M8 6V3h4.5c4 0 4.5 3 4.5 8.5m1.5 3c1.5 2 3 3.25 3 4.5a3 3 0 0 1-6 0c0-1.25 1.5-2.5 3-4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
