<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wb_71ubof"/><path class="em3zn9a_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lightbulb-sharp-duotone" /></template>
<style>
.em3zn9a_e {
  stroke-opacity: 0.4;
  d: path("M8 18L16 18M10 22L14 22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wb_71ubof {
  d: path("M5.1721 14.1737L5.0718 14C4.3697 12.7838 4 11.4043 4 10C4 5.5817 7.5817 2 12 2C16.4183 2 20 5.5817 20 10C20 11.4043 19.6303 12.7838 18.9282 14L18.8279 14.1737");
}

</style>
