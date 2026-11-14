<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ilrqacb-x"/><path class="vx74dnv0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drop-to-floor" /></template>
<style>
.ilrqacb-x {
  d: path("M12 2.5L16.5 5v5L12 12.5L7.5 10V5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vx74dnv0j {
  d: path("M7.5 5L12 7.5L16.5 5M12 7.5v5m0 2.75V18m-2-2l2 2l2-2M3 20.75h18");
}

</style>
