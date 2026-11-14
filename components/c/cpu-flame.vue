<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k_km2sb6f"/><path class="rjib34ral"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cpu-flame" /></template>
<style>
.k_km2sb6f {
  d: path("M4.5 4.5h15v15h-15Zm5-2.5v2.5m5-2.5v2.5m-5 15V22m5-2.5V22M2 9.5h2.5m-2.5 5h2.5m15-5H22m-2.5 5H22");
}

.rjib34ral {
  d: path("M12 16.75c-2.25 0-3.75-1.5-3.75-3.5c0-2.75 2.75-3.5 3-6q2.625 1.5 3 3.75c.5-.5 1-1 1.25-1.75c.5 1.25.25 2.25.25 4c0 2-1.5 3.5-3.75 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
