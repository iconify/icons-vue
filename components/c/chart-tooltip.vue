<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kpcwc9npf"/><path class="spt6qyw1h"/><path class="jybf6-bhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-tooltip" /></template>
<style>
.jybf6-bhw {
  d: path("M11.5 2.5h7a2 2 0 0 1 2 2V6a2 2 0 0 1-2 2h-2L15 10l-1.5-2h-2a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2Zm1 2.75h5");
}

.kpcwc9npf {
  d: path("M2.5 20L7 15.5l4 2l4-4.5l6.5 3.5");
}

.spt6qyw1h {
  fill: currentColor;
  d: path("M13.5 13a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
