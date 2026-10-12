<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xnu2uy2hu"/><path class="cedsapbxy"/><path class="bcyzqbj3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:anteater-sharp" /></template>
<style>
.bcyzqbj3g {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 11.25h.01");
}

.cedsapbxy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.75 11.25c1.75.25 2.5 1.75 2.5 3.75s-.75 3.75-2 5c-.5-2-1.25-4-1.75-6H19Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xnu2uy2hu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.5v-.679l.6-.171L8 10c1.5-2 3.75-3 6-3c2.5 0 4.5 1.75 4.75 4.25L19 14h-2.5v6.25h-2.25v-4H11v4H8.75V15l-1.625-1.219L6 13.5l-2.4-.15l-.6-.171z");
}

</style>
