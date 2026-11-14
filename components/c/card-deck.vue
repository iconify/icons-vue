<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o42wa8bew"/><path class="wltkv2d_v"/><path class="jnxwnibdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:card-deck" /></template>
<style>
.jnxwnibdg {
  d: path("M10 4.75V3.5A1.5 1.5 0 0 1 11.5 2H19a1.5 1.5 0 0 1 1.5 1.5v11A1.5 1.5 0 0 1 19 16h-1.5m-8.25-5l2.25 3.5L9.25 18L7 14.5Z");
}

.o42wa8bew {
  d: path("M4 7.5h10.5v14H4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wltkv2d_v {
  d: path("M7 7.5V6.25a1.5 1.5 0 0 1 1.5-1.5H16a1.5 1.5 0 0 1 1.5 1.5v11a1.5 1.5 0 0 1-1.5 1.5h-1.5");
}

</style>
