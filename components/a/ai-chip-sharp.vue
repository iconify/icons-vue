<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lo0p7bciv"/><path class="ud1651ynu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ai-chip-sharp" /></template>
<style>
.lo0p7bciv {
  d: path("M6.25 6.25h11.5v11.5H6.25z");
}

.ud1651ynu {
  d: path("M12 8.25q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75Zm-2.5-5.5v3.5m5-3.5v3.5m-5 11.5v3.5m5-3.5v3.5M2.75 9.5h3.5m-3.5 5h3.5m11.5-5h3.5m-3.5 5h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
