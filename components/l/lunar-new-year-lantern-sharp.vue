<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rl87yu76c"/><path class="c7-qo9q2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lunar-new-year-lantern-sharp" /></template>
<style>
.c7-qo9q2q {
  d: path("M12 6v11M8.25 6.75c-1.5 3-1.5 6.5 0 9.5m7.5-9.5c1.5 3 1.5 6.5 0 9.5m-7 .75h6.5v2.5h-6.5zM12 19.5v1.75m-1.5-1.75v1.25m3-1.25v1.25");
}

.rl87yu76c {
  d: path("M12 2.75v.75m-3.25 0h6.5V6h-6.5zM12 6c4.75 0 8 2.5 8 5.5S16.75 17 12 17s-8-2.5-8-5.5S7.25 6 12 6Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
