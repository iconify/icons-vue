<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wuobxqbgj"/><path clip-rule="evenodd" class="qthu32b9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bluetooth-connected-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qthu32b9w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 12C7 12.552 6.5523 13 6 13C5.4477 13 5 12.552 5 12C5 11.448 5.4477 11 6 11C6.5523 11 7 11.448 7 12ZM19 12C19 12.552 18.5523 13 18 13C17.4477 13 17 12.552 17 12C17 11.448 17.4477 11 18 11C18.5523 11 19 11.448 19 12Z");
  stroke: none;
}

.wuobxqbgj {
  d: path("M7 7L17 17L12 22V2L17 7L7 17");
}

</style>
