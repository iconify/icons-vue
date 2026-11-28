<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xujddvbqo"/><path clip-rule="evenodd" class="lqbel6y2n"/><path class="sgn99unxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circuit-board-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lqbel6y2n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10 5H14C14.552 5 15 5.448 15 6V13C15 13.552 14.552 14 14 14H6C5.448 14 5 13.552 5 13V6C5 5.448 5.448 5 6 5H10ZM5 17H11V19H5V17ZM15 18C15 18.552 14.552 19 14 19C13.448 19 13 18.552 13 18C13 17.448 13.448 17 14 17C14.552 17 15 17.448 15 18Z");
  stroke: none;
}

.sgn99unxk {
  d: path("M18 7H23M18 12H23M18 17H23");
}

.xujddvbqo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 12V22C19 22.552 18.552 23 18 23H2C1.448 23 1 22.552 1 22V2C1 1.448 1.448 1 2 1H18C18.552 1 19 1.448 19 2V12Z");
  stroke: none;
}

</style>
