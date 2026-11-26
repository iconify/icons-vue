<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ruqp4sbio"/><path class="ecouuhbpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:kerning-duotone" /></template>
<style>
.ecouuhbpe {
  d: path("M7 20H17M9 18L7 20L9 22M15 18L17 20L15 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ruqp4sbio {
  stroke-opacity: 0.4;
  d: path("M2 14L3.7857 9L6.0583 2.668C6.3743 1.783 7.6257 1.783 7.9417 2.668L10.2143 9L12 14M10.2143 9H3.7857M13 2L16.6525 13.332C16.9369 14.217 18.0631 14.217 18.3475 13.332L22 2");
}

</style>
