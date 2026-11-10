<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="foq_pkzdc"/><path clip-rule="evenodd" class="mnt3azjrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bowling-ball-sharp" /></template>
<style>
.foq_pkzdc {
  d: path("M12 22C17.523 22 22 17.523 22 12C22 6.477 17.523 2 12 2C6.477 2 2 6.477 2 12C2 17.523 6.477 22 12 22Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mnt3azjrr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.5 7.5C13.5 8.328 12.828 9 12 9C11.172 9 10.5 8.328 10.5 7.5C10.5 6.672 11.172 6 12 6C12.828 6 13.5 6.672 13.5 7.5ZM18 10.5C18 11.328 17.328 12 16.5 12C15.672 12 15 11.328 15 10.5C15 9.672 15.672 9 16.5 9C17.328 9 18 9.672 18 10.5ZM12 13.5C12 14.328 11.328 15 10.5 15C9.672 15 9 14.328 9 13.5C9 12.672 9.672 12 10.5 12C11.328 12 12 12.672 12 13.5Z");
  stroke: none;
}

</style>
