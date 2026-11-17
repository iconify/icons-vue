<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hmadl4byg"/><path class="dgcs7qlis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-electric-sharp-duotone" /></template>
<style>
.dgcs7qlis {
  d: path("M13.293 7.7071L10 11H14L10.707 14.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hmadl4byg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.647 3.0107C16.987 3.0613 17.281 3.2842 17.419 3.6055L19.307 8H21.5V10H21.479C21.797 10.1733 22 10.5083 22 10.8779V20C22 20.5523 21.552 21 21 21H17.5C17.041 21 16.642 20.6874 16.53 20.2422L16.22 19H7.78L7.47 20.2422C7.358 20.6874 6.959 21 6.5 21H3C2.448 21 2 20.5523 2 20V10.8779C2 10.5083 2.203 10.1733 2.521 10H2.5V8H4.692L6.581 3.6055L6.649 3.4736C6.83 3.1822 7.15 3.0001 7.5 3H16.5L16.647 3.0107Z");
  stroke: none;
}

</style>
