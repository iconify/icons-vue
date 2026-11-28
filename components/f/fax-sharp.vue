<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rcg_q3bha"/><path class="towg9abul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fax-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rcg_q3bha {
  d: path("M3 3L9 3L9 9L21 9L21 21L3 21ZM9 9L9 21M13 9L13 5L18 5L18 9");
}

.towg9abul {
  fill: currentColor;
  d: path("M14 13C14 13.5523 13.5523 14 13 14C12.4477 14 12 13.5523 12 13C12 12.4477 12.4477 12 13 12C13.5523 12 14 12.4477 14 13ZM18 13C18 13.5523 17.5523 14 17 14C16.4477 14 16 13.5523 16 13C16 12.4477 16.4477 12 17 12C17.5523 12 18 12.4477 18 13ZM14 17C14 17.5523 13.5523 18 13 18C12.4477 18 12 17.5523 12 17C12 16.4477 12.4477 16 13 16C13.5523 16 14 16.4477 14 17ZM18 17C18 17.5523 17.5523 18 17 18C16.4477 18 16 17.5523 16 17C16 16.4477 16.4477 16 17 16C17.5523 16 18 16.4477 18 17Z");
  stroke: none;
}

</style>
