<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sf2sj2ugl"/><path class="b5hrn_bgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:astronaut-helmet-sharp" /></template>
<style>
.b5hrn_bgg {
  d: path("M7 7.25h10v6H7zm-.5 11.5h11v2.5h-11z");
}

.sf2sj2ugl {
  d: path("M12 2.75a8 8 0 0 1 8 8v5.5H4v-5.5a8 8 0 0 1 8-8Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
