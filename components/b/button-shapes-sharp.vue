<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e408uacwa"/><path class="geui7dbst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:button-shapes-sharp" /></template>
<style>
.e408uacwa {
  d: path("M2.75 6.25h18.5v11.5H2.75z");
}

.geui7dbst {
  d: path("m7.25 13.25l2.25-4.5l2.25 4.5M8 11.75h3m2.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3-1.5v3m-9 2h9");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
