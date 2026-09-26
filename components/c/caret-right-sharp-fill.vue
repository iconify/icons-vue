<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rnn0xubrz"/><path class="rsy5g76ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-right-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rnn0xubrz {
  fill: currentColor;
  d: path("M17.7413 12.456L6.7841 18.9273C6.4365 19.1326 6 18.8787 6 18.4713L6 5.5287C6 5.1213 6.4365 4.8674 6.7841 5.0727L17.7413 11.544C18.0862 11.7477 18.0862 12.2523 17.7413 12.456Z");
  stroke: none;
}

.rsy5g76ue {
  d: path("M18 12L6 19L6 5L18 12Z");
}

</style>
