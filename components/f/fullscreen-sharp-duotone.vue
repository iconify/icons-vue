<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="mcsnw-7-k"/><path class="ni_d926rs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mcsnw-7-k {
  stroke-opacity: 0.4;
  d: path("M13 3L21 3L21 11M13.7071 10.2929L20.8243 3.1757");
}

.ni_d926rs {
  d: path("M11 21L3 21L3 13M10.2929 13.7071L3.1757 20.8243");
}

</style>
