<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fzhbw2bat"/><path class="g5kxaebbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-2-two-tone" /></template>
<style>
.fzhbw2bat {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 6H19V19C19 21.2091 17.2091 23 15 23H9C6.79086 23 5 21.2091 5 19V6Z");
  stroke: none;
}

.g5kxaebbi {
  d: path("M10 2H14M4 7H20M6 7H18V19C18 20.6569 16.6569 22 15 22H9C7.34315 22 6 20.6569 6 19V7ZM10 11L10 18M14 11L14 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
