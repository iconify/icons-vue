<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jyc2296xb"/><path class="cvdg6jsps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:community-events" /></template>
<style>
.cvdg6jsps {
  d: path("M7.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-1.75 10C5.75 19 7.5 17 10 17s4.25 2 4.25 4.5m.73-12.614a2.25 2.25 0 1 1 .379 4.33M15.75 16c1.75.25 2.25 1.25 2.25 2.5");
}

.jyc2296xb {
  d: path("M3 4.5h18v17H3Zm5-2V6m8-3.5V6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
