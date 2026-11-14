<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aktlyib2c"/><path class="v0_j_9b8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clamp-lab" /></template>
<style>
.aktlyib2c {
  d: path("M5 2.5v19m-2 0h6m-4-15h8.5m0-3.5v6.5a5 5 0 1 0 3 0V3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0_j_9b8t {
  d: path("M12.25 6.5a2.75 1.25 0 1 0 5.5 0a2.75 1.25 0 1 0-5.5 0Z");
}

</style>
