<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ic2-jabyd"/><path class="a1_30kz7g"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fact-check-clock" /></template>
<style>
.a1_30kz7g {
  d: path("m6.5 10.5l3 3L15 8m-.25 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ic2-jabyd {
  d: path("M12 19H2.5V2.5H19V12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
