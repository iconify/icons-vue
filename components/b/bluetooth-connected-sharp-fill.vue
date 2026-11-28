<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jdh-6rbak"/><path clip-rule="evenodd" class="gh5hvr37w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bluetooth-connected-sharp-fill" /></template>
<style>
.gh5hvr37w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 12C7 12.552 6.552 13 6 13C5.448 13 5 12.552 5 12C5 11.448 5.448 11 6 11C6.552 11 7 11.448 7 12ZM19 12C19 12.552 18.552 13 18 13C17.448 13 17 12.552 17 12C17 11.448 17.448 11 18 11C18.552 11 19 11.448 19 12Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jdh-6rbak {
  d: path("M6.707 6.707L17 17L12 22V2L17 7L6.707 17.293");
}

</style>
