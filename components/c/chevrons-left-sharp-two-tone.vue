<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e1ktlybjb"/><path class="q-wnakbbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-left-sharp-two-tone" /></template>
<style>
.e1ktlybjb {
  stroke-opacity: 0.4;
  d: path("M11.2929 17.2929L6 12L11.2929 6.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q-wnakbbs {
  d: path("M18.2929 17.2929L13 12L18.2929 6.7071");
}

</style>
