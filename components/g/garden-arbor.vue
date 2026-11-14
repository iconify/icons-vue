<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fsaclzbqn"/><path class="u5saiab7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-arbor" /></template>
<style>
.fsaclzbqn {
  d: path("M6 20.5V10a6 6 0 0 1 12 0v10.5M3.5 7h17m-18 13.5h19M6 17c-2.5 0-3.5-1.5-3.5-3.5C5 13.5 6 15 6 17Z");
}

.u5saiab7u {
  d: path("M6 13.5c2.5 0 3.5-1.5 3.5-3.5C7 10 6 11.5 6 13.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
