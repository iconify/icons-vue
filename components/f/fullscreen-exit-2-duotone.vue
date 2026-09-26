<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nl56xfbkf"/><path class="scb4y_uru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit-2-duotone" /></template>
<style>
.nl56xfbkf {
  stroke-opacity: 0.4;
  d: path("M21 10L14.5 10C14.2239 10 14 9.7761 14 9.5L14 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.scb4y_uru {
  d: path("M3 14L9.5 14C9.7761 14 10 14.2239 10 14.5L10 21");
}

</style>
