<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c87g3vw6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-up-sharp-fill" /></template>
<style>
.c87g3vw6d {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 2L6 3L6 21M2.7071 17.7071L3 18L6 21L9 18L9.2929 17.7071M18 22L18 21L18 3M14.7071 6.2929L15 6L18 3L21 6L21.2929 6.2929");
}

</style>
