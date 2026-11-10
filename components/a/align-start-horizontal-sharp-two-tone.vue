<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ej-_yqbom"/><path class="oq80a5bcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-start-horizontal-sharp-two-tone" /></template>
<style>
.ej-_yqbom {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 5C10.552 5 11 5.448 11 6V22C11 22.552 10.552 23 10 23H4C3.448 23 3 22.552 3 22V6C3 5.448 3.448 5 4 5H10ZM20 5C20.552 5 21 5.448 21 6V14C21 14.552 20.552 15 20 15H14C13.448 15 13 14.552 13 14V6C13 5.448 13.448 5 14 5H20ZM23 3H1V1H23V3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oq80a5bcr {
  d: path("M23 2H1M20 6H14V14H20V6ZM10 6H4V22H10V6Z");
}

</style>
