<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rx1c9hbvz"/><path class="g86fdm6kx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-cloud-sharp" /></template>
<style>
.g86fdm6kx {
  d: path("M9.8705 10.7535L10.5816 15.4178M13.8248 10.1507L14.5359 14.815");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rx1c9hbvz {
  d: path("M6 19L18 19C20.2091 19 22 17.2091 22 15C22 12.7909 20.2091 11 18 11C18 7.6863 15.3137 5 12 5C8.6863 5 6 7.6863 6 11C3.7909 11 2 12.7909 2 15C2 17.2091 3.7909 19 6 19Z");
}

</style>
