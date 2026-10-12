<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="se2gw3cpr"/><path class="pfbzi9b-v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:invert-colors-sharp" /></template>
<style>
.pfbzi9b-v {
  d: path("M12 2.75c3.5 4 6.5 7.5 6.5 11a6.5 6.5 0 0 1-6.5 6.5Z");
}

.se2gw3cpr {
  d: path("M12 2.75c3.5 4 6.5 7.5 6.5 11a6.5 6.5 0 0 1-13 0c0-3.5 3-7 6.5-11Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
