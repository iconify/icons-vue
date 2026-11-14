<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vfpcmtbqe"/><path class="p58_jqboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hill-climb-bike" /></template>
<style>
.p58_jqboz {
  d: path("m5 12.5l2.75-5.75l5.5 1m0 0L12 3.5h2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vfpcmtbqe {
  d: path("m2.5 20l19-11m-19 3.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8.25-4.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
