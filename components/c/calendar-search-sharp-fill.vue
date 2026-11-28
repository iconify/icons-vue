<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="shq-unx_p"/><path class="hnok46pmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-search-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hnok46pmy {
  d: path("M8 2L8 8M16 2L16 8M20 17.5C20 18.8807 18.8807 20 17.5 20C16.1193 20 15 18.8807 15 17.5C15 16.1193 16.1193 15 17.5 15C18.8807 15 20 16.1193 20 17.5ZM19.2678 19.2678L21.2929 21.2929");
}

.shq-unx_p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 4L21 4C21.5523 4 22 4.4477 22 5L22 11C22 11.5523 21.5523 12 21 12L12 12L12 21C12 21.5523 11.5523 22 11 22L3 22C2.4477 22 2 21.5523 2 21L2 5C2 4.4477 2.4477 4 3 4ZM6 10L6 12L18 12L18 10Z");
  stroke: none;
}

</style>
